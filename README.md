# 🖥️ Windows Server Lab

เอกสารนี้ใช้สำหรับบันทึกการทำ Lab Windows Server ตั้งแต่พื้นฐานจนถึงระดับที่สามารถนำไปใช้งานจริงได้  
**ผู้เขียน:** kuson1999  
**วัตถุประสงค์:** ฝึกปฏิบัติและทำความเข้าใจการติดตั้ง การตั้งค่า และการจัดการ Windows Server

---

## 🔧 สิ่งที่ต้องเตรียม

- Windows Server ISO (เช่น Windows Server 2019 หรือ 2022)
- โปรแกรม Virtual Machine (VMware, VirtualBox หรือ Hyper-V)
- Windows 10/11 สำหรับ Client
- เน็ตเวิร์คจำลอง (Internal หรือ Host-Only)

---

## 🧪 Lab Contents

### 📁 01. ติดตั้ง Windows Server
- ติดตั้ง Windows Server บน VM
- ตั้งชื่อเครื่อง และ IP แบบ Static
- ตั้งเวลา, Region และเปิด Remote Desktop

### 📁 02. ติดตั้ง Active Directory (AD DS)
- Promote เป็น Domain Controller
- สร้าง Domain: `yourdomain.local`
- Join Client เข้า Domain

### 📁 03. Group Policy
- สร้าง Group Policy Object (GPO)
- ตั้งค่า: Wallpaper, Disable USB, Software Restriction

### 📁 04. DNS และ DHCP
- ติดตั้งและตั้งค่า DNS
- ติดตั้ง DHCP และแจก IP ให้อัตโนมัติ
- สร้าง Reservation และ Scope Options

### 📁 05. File Server & Permissions
- แชร์โฟลเดอร์ให้ผู้ใช้
- ตั้ง NTFS และ Share Permission
- สร้าง Home Folder อัตโนมัติ

### 📁 06. User & Group Management
- สร้าง Users และ Groups ใน AD
- ใช้ Group Permissions เพื่อควบคุมการเข้าถึง

### 📁 07. Backup & Restore
- ใช้ Windows Server Backup
- ตั้ง Schedule Backup และทดลอง Restore

### 📁 08. WSUS (Windows Update Server)
- ติดตั้ง WSUS
- กำหนดกลุ่มของเครื่องลูกข่าย
- Sync Update จาก Microsoft

### 📁 09. Remote Access (VPN)
- ติดตั้ง RRAS (Remote and Routing Access)
- ตั้ง VPN Server และ Client

---

## 📝 Notes

- แต่ละ Lab มีโฟลเดอร์ของตัวเอง และมี markdown (`.md`) สำหรับจดรายละเอียด
- แนะนำให้ใช้ VS Code หรือ Obsidian เพื่อเขียน markdown อย่างสะดวก

---

## 📌 License

This lab is created for educational purposes only.
