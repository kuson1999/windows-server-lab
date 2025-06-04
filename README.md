# 🧪 Windows Server 2022 Lab Guide

## ✅ แผนการเรียนรู้สำหรับการใช้งานจริง (Production-ready)

---

## 📁 หมวดพื้นฐานระบบ

| Lab | หัวข้อ | รายละเอียด |
|-----|--------|-------------|
| 01 | ติดตั้ง Windows Server 2022 | แบบ GUI (Desktop Experience) |
| 02 | ตั้งค่า IP, เปลี่ยนชื่อเครื่อง, เปิด Remote Desktop | สำหรับใช้งานในระบบ |
| 03 | ตั้งค่า Windows Update และ Time Sync | อัปเดตระบบและตั้งเวลาให้ตรง |
| 04 | ติดตั้ง Role และ Feature | ผ่าน Server Manager |

---

## 🏢 หมวด Active Directory (AD DS)

| Lab | หัวข้อ | รายละเอียด |
|-----|--------|-------------|
| 05 | ติดตั้ง AD Domain Services | สร้าง Domain Controller |
| 06 | Join เครื่อง Client เข้าระบบ Domain | เช่น Windows 10/11 |
| 07 | จัดการ User, Group, OU | พร้อมกำหนดนโยบายพื้นฐาน |
| 08 | Group Policy (GPO) เบื้องต้น | เช่น ปิด USB, Lock Screen |
| 09 | Delegate Control | มอบสิทธิ์ย่อยให้ดูแล OU |
| 10 | Backup & Restore AD | ด้วย Windows Server Backup |

---

## 🌐 หมวด Network Services

| Lab | หัวข้อ | รายละเอียด |
|-----|--------|-------------|
| 11 | ติดตั้ง DNS Server | ใช้งานร่วมกับ AD |
| 12 | ติดตั้ง DHCP Server | แจก IP ให้ Client |
| 13 | DHCP Reservation | ล็อก IP แบบถาวรตาม MAC |
| 14 | ติดตั้ง WINS (เสริม) | สำหรับระบบเก่า ๆ ที่ยังใช้อยู่ |

---

## 📁 หมวด File Services

| Lab | หัวข้อ | รายละเอียด |
|-----|--------|-------------|
| 15 | ติดตั้ง File Server Role | เปิดใช้บริการไฟล์เซิร์ฟเวอร์ |
| 16 | แชร์โฟลเดอร์ + NTFS Permissions | จัดสิทธิ์ Read/Write อย่างปลอดภัย |
| 17 | สร้าง Home Folder อัตโนมัติ | เชื่อมกับบัญชีผู้ใช้ |
| 18 | Quota และ File Screening | จำกัดขนาด/ชนิดไฟล์ที่อนุญาต |

---

## 🛡️ หมวด Security & Audit

| Lab | หัวข้อ | รายละเอียด |
|-----|--------|-------------|
| 19 | เปิดใช้ Windows Defender + Policy | ป้องกันไวรัสเบื้องต้น |
| 20 | Audit Policy | ตรวจสอบการลบ/แก้ไขไฟล์ |
| 21 | Password & Account Lockout Policy | ป้องกัน Brute-force |

---

## 🧩 หมวดเสริมที่ควรรู้

| Lab | หัวข้อ | รายละเอียด |
|-----|--------|-------------|
| 22 | ติดตั้ง Certificate Services (CA) | ใช้สำหรับระบบ SSL ภายใน |
| 23 | ติดตั้ง IIS Web Server | ทดสอบการรันเว็บภายใน |
| 24 | ติดตั้ง Remote Access (VPN) | ให้พนักงานเชื่อมต่อจากภายนอก |
| 25 | ติดตั้ง Windows Admin Center | บริหารผ่าน Web GUI |
| 26 | ใช้ PowerShell จัดการ Server | สั่งงานแบบอัตโนมัติ |
| 27 | Clone/Template VM | สำหรับการ Deploy เร็วขึ้น |

---

## 🎯 หมวดการจัดการระบบในโลกจริง

- วิเคราะห์ Event Logs เพื่อแก้ไขปัญหา
- สำรองและกู้คืนระบบด้วย Veeam / Windows Server Backup
- สร้าง Lab ทดสอบหลาย DC หรือ DHCP Failover
- ส่ง Logs จาก Windows Server ไปยัง Zabbix / SIEM

---

> 📝 หมายเหตุ: Lab เหล่านี้เหมาะสำหรับผู้ดูแลระบบในองค์กร และสามารถปรับใช้ในสภาพแวดล้อมการทำงานจริงได้

