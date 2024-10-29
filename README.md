# Example คือ ledc.fade
ตัวอย่างนี้แสดงให้เห็นถึงการควบคุมความเข้มของ LED ทำให้สว่างและดับลงอย่างช้าๆตามการ Set Delay

อย่างแรก Show Example แล้วหา Ledc.fade

![image](https://github.com/user-attachments/assets/db112cfe-52ee-4a82-b1a9-691c377a8139)

ต่อสาย GPIO ตามต้องการในที่นี้ใช้

![image](https://github.com/user-attachments/assets/260d7bb9-c742-457b-8139-bfb0fce99e0b)

จากนั้นทำการ Build และ Flash ลงบอร์ด

![image](https://github.com/user-attachments/assets/0203f1e5-3613-44eb-bfca-dc3a3ff1daef)

จะสังเกตได้ว่า LED 0,1 จะสว่างไม่เท่ากับ 2,3 แสดงว่า LED ทั้งสองชุดใช้คนละดีเลย์กัน


โดยที่สามารถกำหนดดีเลยได้ที่

![image](https://github.com/user-attachments/assets/7295a3c1-fcf9-44fe-b989-90c5358f2981)


ใน Serial Moniter แสดง สถานะของ LED

![image](https://github.com/user-attachments/assets/9c992ce3-73b4-483e-8eac-8d37b125d046)



