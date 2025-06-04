# 🖥️ Windows Server Lab Notes

รวมขั้นตอนการติดตั้งและตั้งค่า Windows Server สำหรับใช้งานในองค์กร

## 🔧 สิ่งที่ใช้ในการทำ Lab

- OS: Windows Server 2019 / 2022
- Hypervisor: VMware Workstation / VirtualBox
- ฟีเจอร์ที่ทดสอบ:
  - AD DS (Active Directory Domain Services)
  - DHCP, DNS
  - File Server
  - Group Policy (GPO)

---

## 🧪 Lab 01 - ติดตั้ง Windows Server

### 🔹 ขั้นตอน
1. ดาวน์โหลด ISO Windows Server
2. สร้างเครื่อง VM บน VMware
3. ตั้งค่าพื้นฐาน (CPU, RAM, HDD)
4. Boot ด้วย ISO และติดตั้ง

### 📝 Note
> ควรตั้งชื่อเครื่องให้สื่อความ เช่น `SRV-DC01`

---

## 🧪 Lab 02 - ติดตั้ง AD DS (Domain Controller)

### 🔹 คำสั่ง Powershell

```powershell
Install-WindowsFeature -Name AD-Domain-Services -IncludeManagementTools
