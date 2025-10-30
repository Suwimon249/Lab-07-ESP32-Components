# Lab 7-2: Managed Component from GitHub URL Demo

## ผลลัพธ์ที่คาดหวัง
- การแสดงข้อความการเริ่มต้น sensor จาก GitHub component
- การแสดงข้อมูล temperature และ humidity ทุก 4 วินาที
- การแสดงสถานะการทำงานของ sensor
- การแสดงแหล่งที่มาของ component (GitHub Repository)

## ความแตกต่างจาก Lab 7-1
- Lab 7-1: ใช้ local component (ในเครื่อง)
- Lab 7-2: ใช้ managed component จาก GitHub URL

## การใช้งาน
1. เข้าไปในโฟลเดอร์ lab7-2_Managed_url_Component
2. รันคำสั่ง `idf.py build` (จะดาวน์โหลด component จาก GitHub อัตโนมัติ)
3. ทดสอบด้วย QEMU
