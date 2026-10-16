# Test Summary Report

## สรุปผลการทดสอบ (Test Results)
- **Total Tests:** 6 ข้อ
- **Passed:** 6 ข้อ
- **Failed:** 0 ข้อ

## ข้อผิดพลาดที่พบระหว่างการทำข้อสอบ (Issues Encountered)
- **ปัญหาที่พบ:** ในการรันทดสอบครั้งแรก พบ Error `Test timeout of 30000ms exceeded` ในข้อ `UT-01.1: empty username and password` เนื่องจากเบราว์เซอร์ใช้เวลาโหลดหน้า Login ครั้งแรกนานเกิน 30 วินาที
- **การแก้ไข:** ทำการรันทดสอบใหม่อีกครั้งด้วยคำสั่ง `npx playwright test` หลังจากนั้น Test Scripts สามารถทำงานและผ่าน (Passed) ครบสมบูรณ์ทั้ง 6 ข้อ