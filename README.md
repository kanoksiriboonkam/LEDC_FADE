# Example นี้มีชื่อว่า LEDC_FADE
ซึ่งexample นี้เป็นการทำให้ แสงLEDในบอร์ดesp32 ค่อยๆสว่างและดับ
# ขั้นตอนที่1
### กดที่ show example 
# <img width="415" alt="ภาพถ่ายหน้าจอ 2567-11-01 เวลา 20 09 20" src="https://github.com/user-attachments/assets/df2738c9-08bc-4d63-b052-bc87f1075748">

## ขั้นตอนที่2 
- ค้นหาหรือเลื่อนหาคำว่า Ledc_fade และกดคำว่าLedc_fadeหลังจากนั้นให้กด create project using example Ledc_fade
# <img width="1023" alt="ภาพถ่ายหน้าจอ 2567-11-01 เวลา 19 55 48" src="https://github.com/user-attachments/assets/1feb1b37-2fa8-4bdc-af57-9cad8d77986b">
# ขั้นตอนที่3 
-ต่อขาGPIO18 ไปที่ LED1 ,ต่อขาGPIO19 ไปที่ LED2,ต่อขาGPIO14 ไปที่ LED3,ต่อขาGPIO5 ไปที่ LED4ดังรูป
#  <img width="723" alt="ภาพถ่ายหน้าจอ 2567-11-01 เวลา 20 20 40" src="https://github.com/user-attachments/assets/6560488d-b720-456e-b61f-986adc85975d">
# ขั้นตอนที่4 build
- หลังจากทำขั้นตอนที่3เสร็จเรียบร้อยแล้วให้ทำการ build  
#  <img width="1008" alt="ภาพถ่ายหน้าจอ 2567-11-01 เวลา 20 03 02" src="https://github.com/user-attachments/assets/7a004adb-9ac4-40ad-ac02-fedefe76df12">
- หลังจากทำการbuildในขั้นตอนที่4เสร็จ จะได้ผลลัพธ์คือ LEDค่อยๆสว่างและค่อยๆดับ

# ปรับปรุงแก้ไข้ในการใช้งานได้ดังนี้
- ในส่วนที่ 2 ตรงบรรทัดที่63 ดังรูปจะเป็นการปรับค่าความสว่างและดับของLED ให้เร็วขึ้นหรือช้าลง
# ![รูปภาพ (5)-1](https://github.com/user-attachments/assets/a03207f6-f80c-4523-9a50-594098f66899)
