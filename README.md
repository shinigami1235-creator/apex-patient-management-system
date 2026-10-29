# Apex Patient Management System

ระบบจัดการผู้ป่วยของ Apex Medical Center สำหรับคอมพิวเตอร์สาขา (Windows 10 หรือ 11 แบบ 64 บิต) แท็บเล็ตและแล็ปท็อปของแพทย์เชื่อมต่อเข้าคอมพิวเตอร์เครื่องนี้ผ่าน wifi ของสาขา

**[ดาวน์โหลดตัวติดตั้ง (Apex-PMS-Setup.exe)](https://github.com/shinigami1235-creator/apex-patient-management-system/raw/main/Apex-PMS-Setup.exe)**

## ติดตั้ง

1. ดาวน์โหลดตัวติดตั้งจากลิงก์ด้านบน แล้วดับเบิลคลิกไฟล์
2. Windows จะขึ้นว่า "Windows protected your PC" เพราะตัวติดตั้งยังไม่มีลายเซ็นดิจิทัล กด **More info** แล้วกด **Run anyway** จากนั้นกด **Yes**
3. เลือกภาษา กด Next แล้วกด Install โปรแกรมจะติดตั้งที่ `C:\Apex PMS`
4. ติ๊ก "เปิดระบบจัดการผู้ป่วย Apex" ไว้ แล้วกด Finish หน้าต่างสีดำจะเปิดขึ้นพร้อมหน้าตั้งค่าในเบราว์เซอร์ เปิดหน้าต่างสีดำไว้ตลอดเวลาที่สาขาทำงาน
5. ครั้งต่อไปให้เปิดจากไอคอน **Apex PMS** บนหน้าจอ

ตั้งค่าแท็บเล็ตที่ **ตั้งค่า › อุปกรณ์ › เชื่อมต่อ** แล้วสแกน QR ด้วยแท็บเล็ต

## อัปเดต

โปรแกรมตรวจหาเวอร์ชันใหม่เองเมื่อเปิดและทุกหกชั่วโมง แล้วดาวน์โหลดไว้เบื้องหลัง เมื่อพร้อม หน้าวันนี้จะขึ้นว่า "เวอร์ชัน … พร้อมแล้ว"

- ตอนเลิกงาน กด **ปิด** ที่ด้านบนของหน้าจอบนคอมพิวเตอร์สาขา แล้วเลือก **อัปเดตแล้วปิด** เปิดหน้าต่างสีดำไว้ประมาณหนึ่งนาที หน้าต่างจะปิดเองเมื่อติดตั้งเสร็จ
- ถ้าปิดหน้าต่างสีดำด้วยปุ่ม X ครั้งต่อไปที่เปิดโปรแกรมจะถามก่อนแล้วติดตั้งเองภายใน 15 วินาที
- ติดตั้งด้วยมือ: ปิดโปรแกรมก่อน แล้วดับเบิลคลิก `update.bat` ในโฟลเดอร์ `C:\Apex PMS`

ข้อมูลผู้ป่วยในโฟลเดอร์ `data` และไฟล์สำรองในโฟลเดอร์ `backups` ไม่ถูกแตะต้อง

## ถอนการติดตั้ง

Start › Apex PMS › Uninstall Apex PMS ข้อมูลผู้ป่วยและไฟล์สำรองยังอยู่ที่ `C:\Apex PMS\data` และ `C:\Apex PMS\backups` จนกว่าจะลบเอง

---

## English

The Apex Medical Center patient management system, for the branch PC (Windows 10 or 11, 64-bit). Doctors' tablets and laptops connect to this PC over the branch wifi.

**[Download the installer (Apex-PMS-Setup.exe)](https://github.com/shinigami1235-creator/apex-patient-management-system/raw/main/Apex-PMS-Setup.exe)**

**Install**

1. Download the installer from the link above and double-click it.
2. Windows says "Windows protected your PC", since the installer isn't digitally signed yet. Press **More info**, then **Run anyway**, then **Yes**.
3. Pick a language, press Next, then Install. It installs to `C:\Apex PMS`.
4. Leave "Start the Apex Patient Management System" ticked and press Finish. A black window opens with the setup page in the browser. Keep the black window open while the branch is working.
5. From then on, open it from the **Apex PMS** icon on the desktop.

Set up the tablets under **Settings › Devices › Connect** and scan the QR with each tablet.

**Update**

The program looks for a new version when it starts and every six hours and downloads it in the background. When it's ready, Today says "Version … is ready".

- At the end of the day, press **Close** at the top of the screen on the branch PC and choose **Update and close**. Keep the black window open for about a minute; it closes by itself when the update is in.
- If the black window was closed with the X, the next start asks first and installs by itself after 15 seconds.
- By hand: close the program, then double-click `update.bat` in `C:\Apex PMS`.

The patient data in the `data` folder and the backups in the `backups` folder are never touched.

**Uninstall**

Start › Apex PMS › Uninstall Apex PMS. The patient data and backups stay in `C:\Apex PMS\data` and `C:\Apex PMS\backups` until you delete them.

The models folder holds the files the before and after picture tool downloads onto the branch PC the first time they're needed.

Version 1.5.3 · SHA-256 `da5dda17cc6771d238ae60a162b5fcef45aaa8a807d5fa1c452a21fac918a4e8`
