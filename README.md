# ชื่อโครงงาน : Mole Destroyer - เกมทำลายตุ่น

โครงงานนี้เป็นส่วนหนึ่งของรายวิชา 01204322 Embedded System ภาคปลาย ปีการศึกษา 2566 หมู่ 1

------------------------------------------------------------------------

## สมาชิกผู้จัดทำ:  
> นิสิตภาควิชาวิศวกรรมคอมพิวเตอร์ คณะวิศวกรรมศาสตร์ มหาวิทยาลัยเกษตรศาสตร์ วิทยาเขตบางเขน  

6410500246 นายณัฐฐากร สินอำนวยผล  
6410504039 นายชัยธวัช สีน้ำเงิน  
6410504314 นายวิชานนท์ วิชชุกรศักดิ์  
6410504322 นายวิทวัส พงศ์พฤติ  
6410504349 นายศุภนัฏ วิสิฏกตัญญูชัย  
6410504357 นายสรัลรักษ์ ดำกุล  

------------------------------------------------------------------------

## รายละเอียดไฟล์:

```
├── MoleDestroyer
│   ├── Images
│   ├── Schematic
│   ├── SourceCode
│   │   ├── bonk-controller1
│   │   ├── bonk-controller2
│   │   ├── mole-controller1
│   │   └── mole-controller2
│   ├── license.txt
│   └── README.md
```

ซึ่งมีรายละเอียดดังนี้

| ไฟล์/ไดเรคทอรี | รายละเอียด |
|--------------|-----------|
| `Images` | ไดเรคทอรีนี้ประกอบไปด้วยรูปภาพของสมาชิกและรูปภาพของตัวชิ้นงาน |
| `Schematic` | ไดเรคทอรีนี้ประกอบไปด้วยรูปภาพที่แสดงแผนภาพ schematic ของ board ทั้งหมด |
| `SourceCode` | ไดเรคทอรีนี้ประกอบไปด้วย source code ของ board ทั้งหมด |
| `bonk-controller1` | ไดเรคทอรีนี้ประกอบไปด้วย source code ของ board ที่เป็น controller หลักสำหรับ player 1 |
| `bonk-controller2` | ไดเรคทอรีนี้ประกอบไปด้วย source code ของ board ที่เป็น controller หลักสำหรับ player 2 |
| `mole-controller1` | ไดเรคทอรีนี้ประกอบไปด้วย source code ของ board ที่เป็นตัวเล่นสำหรับ player 1 |
| `mole-controller2` | ไดเรคทอรีนี้ประกอบไปด้วย source code ของ board ที่เป็นตัวเล่นสำหรับ player 2 |
| `license.txt` | ไฟล์นี้แสดงเงื่อนไขการอนุญาตให้ผู้อื่นนำงานของตนเองไปใช้ |
| `README.md` | ไฟล์นี้แสดงรายละเอียดของของไฟล์ที่เกี่ยวข้องและรายละเอียดต่างๆ ของโครงงาน |

------------------------------------------------------------------------

## อุปกรณ์ที่ใช้:

- NodeMCU ESP-32S [6 ตัว]
- Push Button ขนาด 6 mm [5 ตัว]
- 0.96" I2C 128x64 OLED Display [6 ตัว]
- SG90 Servo Motor [4 ตัว]
- LDR Photoresistor Sensor Module [4 ตัว]
	
------------------------------------------------------------------------