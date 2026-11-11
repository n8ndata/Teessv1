ROUTER CENTRAL SYSTEM
=====================

วิธีใช้งาน
1. แตกไฟล์ ZIP ทั้งหมด
2. เปิด index.html เพื่อเข้าหน้าเลือกโหมด
3. เลือก Machine Analytics หรือ Multi-Machine System
4. กดปุ่ม "หน้าหลัก / เปลี่ยนโหมด" ด้านบนเพื่อกลับมาเลือกอีกโหมด

โครงสร้าง
- index.html : หน้าแรก / ตัวเลือกโหมด
- machine-analytics/index.html : ROUTER Machine Analytics & Downtime Dashboard
- multi-machine/index.html : ROUTER Multi-Machine Central Dashboard
- multi-machine/google_apps_script_complete_code.js : Google Apps Script ของระบบ Multi-Machine
- multi-machine/README_ADMIN_SETUP.txt : คู่มือตั้งค่าเดิม

หมายเหตุ
- เก็บโฟลเดอร์และไฟล์ทั้งหมดไว้ในตำแหน่งเดิม ห้ามย้าย index.html ของแต่ละโหมดออกจากโฟลเดอร์
- ทั้งสองระบบถูกฝังในหน้าแม่ผ่าน iframe เพื่อแยก CSS/JavaScript และลดโอกาสชนกันของชื่อฟังก์ชัน/element ID
- ระบบเดิมและการเชื่อมต่อ Google Sheets/Firebase ภายในแต่ละโหมดยังคงใช้โค้ดต้นฉบับจาก ZIP ที่ได้รับ
- การใช้งานผ่านกล้อง/การเชื่อมต่อบางบริการอาจต้องเปิดผ่าน HTTPS หรือ localhost แทน file://
