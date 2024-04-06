
# Instructure Image

Date: 2024-03-31

## Status

Accepted

## Context

การแสดงผลของ Couse Detail

## Decision

- หน้าจอนี้จะแสดงขึ้นมาเมื่อกดเข้ามาจากหน้า Course List
- แปลงรูปของ Trainer ที่เกี่ยวข้องใน Course นี้ไว้ในรูป based64 แล้วเก็บไว้ใน mongo เพราะจะได้ไม่ต้องเสียเวลาโหลด
- แสดง Trainer ได้มากกว่า 1 คน
- แสดงรูปภาพได้สูงสุด 4 ภาพ หากไม่มีภาพจะไม่แสดง
- แสดง Class List ที่อยู่ใน Course นี้ทั้งหมดไว้ใน Course Detail
- Backend ใช้ Node.js กับ Express
- Database ใช้ MongoDB
- Infra ใช้ของ AWS
