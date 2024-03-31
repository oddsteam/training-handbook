# Instructure Image

Date: 2024-03-31

## Status

Accepted

## Context

ทุก ๆ ทีมถนัดพวก Framework ที่เป็น JavaScript และถนัดในการแยก Frontend กับ Backend

## Decision

- เก็บรูปของ Instructure แต่ละ Class ไว้ใน source.public เพราะจะได้ไม่ต้องเสียเวลาโหลด
- Backend ใช้ Node.js กับ Express
- Database ใช้ MongoDB
- Infra ใช้ของ AWS
