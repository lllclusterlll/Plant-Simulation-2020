# Plant Simulation 2020
**Plant Simulation** เป็นโปรแกรมจำลองการทำงานของชุดลำเลียงชิ้นงานด้วยสายพานอย่างง่าย โปรแกรมถูกใช้เป็นสื่อการเรียนการสอนในโครงการ`การประยุกต์ใช้จริงของเทคโนโลยีไอโอทีสำหรับภาคอุตสาหกรรม (Industrial Internet of Things: IIoT) ร่วมกับระบบฝังตัว (Embedded System) เทคโนโลยีความจริงเสริม (Augmented Reality: AR) และคอมพิวเตอร์วิชั่น (Computer Vision)`  โปรแกรมที่ใช้ร่วมกันทั้งหมดอยู่ที่นี่ https://github.com/Cluster-APX/IIoT-System-Integration

## Plant Simulation GUI
![Plant Simulation GUI](Doc/Plant%20Simulation%20Example%20-%202020-06-09%20A%20.jpg)

# Function
- จำลองการทำงานของชุดลำเลียงชิ้นงานด้วยสายพานอย่างง่าย
- จำลองการทำงานของอุปกรณ์ต่าง ๆ ได้แก่ Vision Sensor, Proximity Sensor และ Linear Actuator
- ปรับมุมมองของโปรแกรมได้
- ตั้งค่าตำแหน่งของอุปกรณ์ต่าง ๆ
- เชื่อมต่อกับ Application ภายนอกผ่าน Serial Port และ Spout

# System Overview
![System Overview](Doc/System%20Overview%20-%202020-06-03%20A.jpg)

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
- [Plant Simulation](Application)

# การใช้งาน
https://github.com/Cluster-APX/IIoT-System-Integration#%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%83%E0%B8%8A%E0%B9%89%E0%B8%87%E0%B8%B2%E0%B8%99