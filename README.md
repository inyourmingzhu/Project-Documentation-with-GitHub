# SALA STORE - Project Design Document
# Project of CSI204 SUMMER SEMESTER 3/2568

## รายละเอียดโปรเจกต์

ระบบ E - Commerce สำหรับร้านขายเสื้อผ้าแบรนด์ SALA รองรับ 3 บทบาทผู้ใช้งาน Customer . Staff , Admin

## USER REQUITEMENT

### CUSTOMER

- เพิ่มสินค้าลงตะกร้า
- ค้นหาสินค้า
- log in / register
- check out
- buy history
- ยื่น ticket support (ขอความช่วยเหลือ/ติดต่อ support)

### ADMIN

- add สินค้า
- delete สินค้า
- เพิ่มหมวดหมู่สินค้า
- แก้ไขสินค้า
- จัดการข้อมูลลูกค้า
- dashboard

### SUPPORT

- ตอบ ticket ลูกค้า


## โครงสร้างโปรเจกต์

```text
Project-Documentation-with-GitHub
│
├── login
│   └── login.html
│   └── markdown.html
│
└── README.md
```

## MERMAID ยังไม่แก้ไขเนื้อหาอะไรเลย
```mermaid
graph TD
    Project[SALA STORE - Project Design Document]

    Features[ฟีเจอร์]
    Tech[เทคโนโลยีที่ใช้ในโปรเจกต์]
    Structure[โครงสร้างโปรเจกต์]

    Project --> Features
    Project --> Tech
    Project --> Structure

    Features --> F1[หน้า Login]
    Features --> F2[กรอก Username / Password]
    Features --> F3[ปุ่ม Login / Register]

    Tech --> T1[HTML5 / CSS3]
    Tech --> T2[Git / GitHub]
    Tech --> T3[Sourcetree / Markdown]

    Structure --> S1[folder: login]
    Structure --> S2[file: README.md]
    S1 --> S1_1[login.html]
    S1 --> S1_2[markdown.html]
```

## ผู้จัดทำ

- ชื่อ : นางสาวภทรพร แซ่ลี้
- รหัสนักศึกษา : 67176203