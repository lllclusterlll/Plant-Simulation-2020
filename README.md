# Plant Simulation 2020
**Plant Simulation** เป็นโปรแกรมจำลองการทำงานของชุดลำเลียงชิ้นงานด้วยสายพานอย่างง่าย โปรแกรมถูกใช้เป็นสื่อการเรียนการสอนในโครงการ`การประยุกต์ใช้จริงของเทคโนโลยีไอโอทีสำหรับภาคอุตสาหกรรม (Industrial Internet of Things: IIoT) ร่วมกับระบบฝังตัว (Embedded System) เทคโนโลยีความจริงเสริม (Augmented Reality: AR) และคอมพิวเตอร์วิชั่น (Computer Vision)`

## Plant Simulation GUI
![Plant Simulation GUI](Doc/Plant%20Simulation%20Example.jpg)

# Function
- จำลองการทำงานของชุดลำเลียงชิ้นงานด้วยสายพานอย่างง่าย
- ตั้งค่าตำแหน่งของอุปกรณ์ ๆ
- ปรับมุมมองเพื่อสำรวจส่วนต่าง ๆ ใน Plant
- ควบคุมการทำงานของอุปกรณ์ (Linear Actuator)
- อ่านค่าจาก Sensor (Vision Sensor และ Proximity Sensor)
- เชื่อมต่อกับ Application ภายนอกผ่าน Modbus และ Spout

# System Overview
![System Overview](Doc/System%20Overview%20-%202020-05-14%20A.jpg)

# System Requirement
- Screen Resolution 1920x1080 (Unity)
- Windows 10
- Spout for Python [[link](https://github.com/spiraltechnica/Spout-for-Python)] (แนบไฟล์ `SpoutSDK.pyd` มาให้แล้ว)
- Miniconda3 Windows 64-bit [[link](https://docs.conda.io/en/latest/miniconda.html)]
  - Python 3.5 (Virtual Environment) [[link](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)]
    - opencv-contrib-python
    - pyopengl
    - pygame

# Application
- [Plant Simulation 2020](Application)
- [System Integration](https://github.com/Cluster-APX/IIoT-System-Integration)

# การใช้งาน
## Plant Simulation (Unity)
- เปิดใช้งาน `FIBO Plant Simulator 2020.exe`
- ตั้งค่า Resolution `1920x1080`

## Computer Vision (Python)
- ตั้งค่า Resolution ใน Code ให้ตรงตาม Plant Simulation
- สำหรับเครื่องที่ใช้ CPU ที่มี APU ต้องทำการตั้งค่าให้ Python ใช้งาน GPU ในการ Redner ดังนี้
  - Nvidia GPU
    - เปิดโปรแกรม NVIDIA Control Panel
    - Manage 3D Setting -> Program Settings
    - `1. Select a program to customize:` = python.exe
    - `2. Select the preferred graphics processor for this program:` = High-performance NVIDIA processor
  - AMD GPU
    - ?
