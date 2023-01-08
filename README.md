# ระบบจองลานกางเต็นท์ผ่าน Web Application
ระบบจองลานกางเต็นท์ผ่าน Web Application ใช้สำหรับจองลานกางเต็นท์ ในยุคนี้ปฏิเสธไม่ได้เลยว่าเทรนการท่องเที่ยวแบบเข้าหาธรรมชาติ กำลังมาแรงและได้รับความนิยมมากขึ้นเรื่อย ๆ ผู้คนจำนวนมาก เริ่มเปลี่ยนแนวมาเป็นสายแคมป์กันมากขึ้น เริ่มกลับสู่วิถีชีวิตที่มีธรรมชาติเป็นตัวเชื่อม ส่วนหนึ่งอาจเพราะการใช้ชีวิตในเมืองที่วุ่นวาย การทำงานที่เคร่งเครียดดังนั้น “แคมป์ปิ้ง” จึงเป็นการท่องเที่ยวที่ตอบโจทย์กับความต้องการนี้เป็นอย่างมาก เพราะเป็นกิจกรรมที่ทำได้ง่าย มีความสนุก เป็นโอกาสที่เราได้เข้าไปอยู่กับธรรมชาติ เสพธรรมชาติ เสพบรรยากาศ ได้ใช้เวลาร่วมกับครอบครัว เพื่อนฝูงและตัวเอง กลุ่มของผมเลยได้ทำ Web Application จองลานกางเต็นท์ขึ้นมาเพื่อตอบโจทย์ของคนที่รักการแคมป์ปิ้ง ชอบกางเต็นท์แต่ไม่รู้ว่าจะไปจองสถานที่ได้ที่ไหนหรือไปจองสถานที่จริงค่อนข้างยุ่งยาก ทางเว็บของเรา “JUSTCAMP” จะช่วยตอบโจทย์และแก้ไขปัญหาตรงนี้ได้ โดยตัวเว็บจะมีการเก็บข้อมูลชื่อ-สกุล วันเช็คอิน วันเช็คเอาท์ สถานที่ที่จะจองลานกางเต็นท์ จำนวนผู้พัก เบอร์โทรศัพท์ติดต่อ และจะแสดงตารางประวัติการจองซึ่งสามารถเพิ่ม ลบ แก้ไขข้อมูล.

## Link  to youtube
[JUSTCAMP ระบบจองลานกางเต็นท์ผ่าน Web Application](https://www.youtube.com/watch?v=C2795INq4B8)

## Data dict
- สถานที่(Location) ใช้เป็นการระบุสถานที่ของลูกค้าที่ต้องการเข้าพัก
- วันเข้าใช้บริการ(Check-in) ใช้เพื่อระบุวัน/เดือน/ปีที่ลูกค้าเข้าพักลงในระบบ ว่ามีการจองสถานที่เป็นจำนวนเท่าไหร่
- วันออก(Check-out) ใช้เพื่อระบุวัน/เดือน/ปีที่ลูกค้าทำการออกจากสถานที่ลงในระบบเพื่อทำการต้อนรับลูกค้าที่มาใช้บริการใหม่
- จำนวนผู้เข้าพัก(Number of guests) ใช้เพื่อยืนยันจำนวนของลูกค้าที่เข้าพักว่ามีจำนวนเท่าไหร่และทำการคิดค่าบริการตามจำนวนผู้เข้าพัก
- ชื่อ-สกุล(Name-surname) ใช้เพื่อยืนยันว่าลูกค้าท่านนี้ได้ทำการจองสถานที่เป็นที่เรียบร้อย
- เบอร์โทร(Telephone) ใช้เพื่อเป็นการติดต่อลูกค้าอีกช่องทางหนึ่งเพื่อยืนยันการจองสถานที่

|  #  | Attribute         | Description   | Data Type     | Example        | 
| ----| -------------     | ------------- | ------------- | -------------  | 
| 1   | Location          | สถานที่         | String        | Pha Hin Dam    |
| 2   | Check-in          | วันเข้าใช้บริการ   | String        | 2023-01-01     |
| 3   | Check-out         | วันออก         | String        | 2023-01-05     |
| 4   | Number of guests  | จำนวนผู้เข้าพัก   | Integer       | 6              |
| 5   | Name-surname      | ชื่อ-สกุล        | String        |jirakid aiadhet |
| 6   | Telephone         | เบอร์โทร        | String        | 0950729219     |

## หน้าตาตัว Web Application
- #### หน้าหลัก
![screencapture-127-0-0-1-5500-home-html-2023-01-08-13_16_31](https://user-images.githubusercontent.com/110581279/211183223-b89d3ee2-2c66-4581-a26c-c81aa74591fb.png)
- #### หน้าจองลานกางเต็นท์
![screencapture-127-0-0-1-5500-booking-html-2023-01-08-13_26_35](https://user-images.githubusercontent.com/110581279/211183554-81c1c4b2-bde7-4fec-a026-5cf4780ba9e0.png)
- #### หน้าหมวดหมู่
![screencapture-127-0-0-1-5500-category-html-2023-01-08-13_18_04](https://user-images.githubusercontent.com/110581279/211183251-860b7dee-476b-4b5b-9bea-656938a09162.png)
- #### หน้าช่องทางการติดต่อ
![screencapture-127-0-0-1-5500-contact-html-2023-01-08-13_18_17](https://user-images.githubusercontent.com/110581279/211183257-5d02748f-9b15-452f-9d80-3f40d988da26.png)

## สมาชิก

- 64102080 นายจิรกิตติ์ เอียดเหตุ
* 64125735 นายธนวัฒน์ กองสีสังข์
+ 64104458 นางสาวณัฐธิดา ยะลา

## มหาวิทยาลัยวลัยลักษณ์ หลักสูตรเทคโนโลยีสารสนเทศและนวัตกรรมดิจิทัล สำนักวิชาสารสนเทศศาสตร์
