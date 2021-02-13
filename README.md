# vite2-beta69-vue3
ทดสอบการ update DOM ด้วย timer กับ vite2 + vue3
เปรียบเทียบจากโจทย์เดียวกัน และใช้ vite (vitejs.dev) เป็น web dev server (โดยหยิบยืม default template ของ vue3 มาเป็นโจทย์) ดังนี้

- มี Hello World Component <HelloWorld /> แสดง Logo framework และ ปุ่ม counter เพิ่มนับค่าจำนวนครั้งของการกดปุ่ม
- มี Timer Component <Timer /> โดยมี dummy text "Lorem Ipsum" .... วางแบบเปลือยๆ เอาไว้ และใช้ setInterval() เพื่อนับเวลาและ update DOM ทุกๆ 1 วินาที

ลองเปรียบเทียบผลลัพธ์ตาม video ด้านล่าง
เราจะเห็นว่า ถึงแม้ผลลัพธ์บน browser จะเห็นผลลัพธ์ที่ไม่แตกต่างกัน
แต่ถ้าเมื่อเราเปิด developer tool ดู จะเห็นว่า vue3 (https://vuejs.org) มีการกระพริบของ DOM ทั้งก้อน เมื่อ DOM ถูก update อยู่ตลอดเวลา

ส่วน svelte3 (https://svelte.dev) จะ update เฉพาะเลข timer ที่เพิ่มขึ้นเท่านั้น และส่วน dummy text "Lorem Ipsum" จะไม่ถูก update เลย ตรงนี้จะเห็นว่า svlelte3 ทำเรื่อง rendering performance ได้ดีมากๆ

😃👏🎉🎉👍👍👍

[<img src="https://img.youtube.com/vi/pjVbgxy_qdM/maxresdefault.jpg" width="50%">](https://www.youtube.com/watch?v=pjVbgxy_qdM)
