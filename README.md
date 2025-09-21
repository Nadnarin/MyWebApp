# MyWebApp
สำหรับการสร้างเว็บพอร์ตโฟลิโอ 3D Model มีขั้นตอนที่สำคัญดังนี้:

## Table of Contents
- [ProjectSetup](#ProjectSetup)
- [body](#body)
    - [InputFormSection](#InputFormSection)
    - [ResultsSection](#ResultsSection)
    - [SummaryCards](#SummaryCards)
    - [Chart](#Chart)
    - [DataTable](#DataTable)
- [script](#script)
    - [กำหนดตัวแปรสำคัญ](#กำหนดตัวแปรสำคัญ)
    - [format](#format)
    - [submit](#submit)
    - [calculateAndDisplay](#calculateAndDisplay)
    - [updateChart](#updateChart)
    - [CopytoClipboard](#CopytoClipboard)
---


## ProjectSetup
- สร้างโฟลเดอร์โปรเจกต์: สร้างโฟลเดอร์หลักสำหรับโปรเจกต์ทั้งหมด
- เริ่มต้นโปรเจกต์: ใช้คำสั่ง npm init -y เพื่อสร้างไฟล์ package.json
- ติดตั้งไลบรารี: ติดตั้งไลบรารีที่จำเป็นสำหรับทั้งฝั่ง Frontend และ Backend ได้แก่:
  - Frontend: npm install three react react-dom
  - Backend: npm install express multer mysql2
  - หมายเหตุ: หากใช้ Vue.js ให้ติดตั้ง vue และ vue-router แทน React และ react-dom
- ติดตั้งเครื่องมือเพิ่มเติม: ติดตั้งไลบรารีสำหรับจัดการไฟล์และเซิร์ฟเวอร์ เช่น cors เพื่ออนุญาตการเชื่อมต่อระหว่าง Frontend และ Backend และ dotenv เพื่อจัดการตัวแปรสภาพแวดล้อม
