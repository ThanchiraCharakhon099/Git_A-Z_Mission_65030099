# คำสั่ง git ที่ขึ้นต้นด้วยอักษร T
# git tag

Git tag คือ ป้ายกำกับที่ระบุตำแหน่งเฉพาะในประวัติการแก้ไขของโปรเจ็กต์ Git สามารถใช้เพื่อระบุเวอร์ชันเฉพาะของโปรเจ็กต์หรือเพื่อติดตามการเปลี่ยนแปลงที่สำคัญ
<br>
Git tag มีสองประเภท:
<br>
- Lightweight tags : เป็นป้ายกำกับแบบธรรมดาที่เชื่อมโยงกับ commit เฉพาะ

- Annotated tags : เป็นป้ายกำกับแบบขยายที่เชื่อมโยงกับ commit เฉพาะและสามารถมีข้อความอธิบายเพิ่มเติมได้
## แสดง Tag ทั้งหมด
git tag

### แสดงเรียงจากวันที่สร้างล่าสุด
git tag --sort=-creatordate

### ค้นหา Tag
git tag -l "keyword" // ระบุคีย์เวิร์ด
<br>
git tag -l "keyword*" // ระบุคีย์เวิร์ดและตามหลังด้วยอะไรก็ได้

### สร้าง Tag
git tag -a <tag_name> -m "ข้อความหมายเหตุ"
