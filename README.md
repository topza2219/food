# Flood Alert System

ระบบแจ้งเตือนน้ำท่วมแบบเรียลไทม์ ที่มีฟีเจอร์:
- ค้นหาสถานะน้ำท่วมในพื้นที่
- แจ้งเตือนแบบเรียลไทม์ผ่าน WebSocket
- แสดงข้อมูลน้ำท่วมในรูปแบบแผนที่ (Leaflet.js)
- ฟอร์มแจ้งเหตุฉุกเฉิน

## การติดตั้ง Backend
1. ติดตั้ง Python และ Node.js
2. ติดตั้ง Flask และ dependencies:
   ```bash
   pip install -r backend/requirements.txt
   ```
3. ติดตั้ง dependencies สำหรับ frontend:
   ```bash
   npm install
   ```
