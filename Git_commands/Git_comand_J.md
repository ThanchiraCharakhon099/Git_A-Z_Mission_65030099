# คำสั่ง git ที่ขึ้นต้นด้วยอักษร J

# git jump : ย้ายไปยัง commit ก่อนหน้าหรือถัดไป

# คำสั่ง git jump

- คำสั่ง git jump ใช้เพื่อย้ายไปยัง commit ก่อนหน้าหรือถัดไป คำสั่งนี้จะย้ายไปยัง commit ที่ระบุโดยตัวเลือก -c หรือ commit ถัดไปหรือก่อนหน้าตามลำดับ

- คำสั่ง git jump มีรูปแบบดังนี้

git jump [options]

# ตัวอย่างการใช้งานคำสั่ง git jump:

###### ย้ายไปยัง commit ก่อนหน้า
git jump -c HEAD^

###### ย้ายไปยัง commit ถัดไป
git jump -c HEAD~
