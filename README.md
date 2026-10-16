# Final Exam: Software Testing

## Integration Testing Explanation
- **IT-01:** ส่วนที่เป็น Real คือหน้า Login ดั้งเดิมของ SauceDemo ส่วนที่เป็น Stub คือหน้า Inventory ที่จำลองโครงสร้าง DOM ขึ้นมาใหม่ด้วย `page.setContent()`
- **IT-02:** ส่วนของ Driver คือฟังก์ชัน `driverOpenInventory()` ที่จำลองการสร้าง Cookie `session-username` เพื่อข้ามการ Login ส่วนที่เป็น Real คือหน้า Inventory และ Shopping Cart จริงของระบบ