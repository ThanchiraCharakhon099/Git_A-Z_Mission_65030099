# คำสั่ง git ที่ขึ้นต้นด้วยอักษร M

# git merge
 คือคำสั่งที่ใช้รวมการเปลี่ยนแปลงจากสาขาหนึ่งเข้ากับอีกสาขาหนึ่ง คำสั่งนี้มักใช้เพื่อรวมการเปลี่ยนแปลงจากสาขาการพัฒนาเข้ากับสาขาหลัก หรือเพื่อรวมการเปลี่ยนแปลงจากสาขาสาขาย่อยเข้ากับสาขาหลัก

เมื่อใช้คำสั่ง git merge Git จะเปรียบเทียบการเปลี่ยนแปลงของทั้งสองสาขาและรวมการเปลี่ยนแปลงที่เหมือนกันเข้าด้วยกัน หากมีการเปลี่ยนแปลงที่ขัดแย้งกัน Git จะหยุดและขอให้คุณแก้ไขความขัดแย้งด้วยตนเอง
### คำสั่งการรวม Branch มายัง Local

# คำสั่ง git merge มีรูปแบบดังนี้

git merge <branch_name>
<br>
โดย <branch_name> คือชื่อของสาขาที่จะรวมเข้ากับสาขาปัจจุบัน

## ตัวอย่างการใช้คำสั่ง git merge

### ย้ายไปที่สาขาหลัก
##### git checkout master

### รวมการเปลี่ยนแปลงจากสาขาการพัฒนา
##### git merge develop
<br>
คำสั่งนี้จะรวมการเปลี่ยนแปลงจากสาขาพัฒนาเข้ากับสาขาหลัก หากมีความขัดแย้ง Git จะหยุดและขอให้แก้ไขความขัดแย้งด้วยตนเอง
เมื่อแก้ไขความขัดแย้งแล้ว สามารถดำเนินการรวมต่อไปได้โดยรันคำสั่ง git merge --continue หรือยกเลิกการรวมโดยรันคำสั่ง git merge --abort
