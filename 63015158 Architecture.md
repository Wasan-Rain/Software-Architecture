# 63015158 Architecture

### *1. matplotlib*

| Software | Purpose | Architectural patterns/styles | Quality Attribute | Resource |
| ----------- | ----------- | ----------| ----------|----------|
| matplotlib | เพื่อสร้างการแสดงภาพแบบสแตติก ภาพเคลื่อนไหว และการวางแผนกราฟิก |  ประกอบด้วยองค์ประกอบหลักสามส่วน คือ Back-end layer, Artist layer, Scripting layer | flexibility, probability, visibility | https://medium.com/@codingpilot25/architecture-of-matplotlib-1a2d44370f5a |
---
### *2. Selenium WebDriver*

| Software | Purpose | Architectural patterns/styles | Quality Attribute | Resource |
| ----------- | ----------- | ----------| ----------|----------|
| Selenium WebDriver | เพื่อใช้ทดสอบเว็บแอปพลิเคชันในเบราว์เซอร์ต่างๆ | ประกอบด้วยองค์ประกอบหลักสี่ส่วน คือ Selenium Client library ให้การสนับสนุนไลบรารีต่างๆ เช่น Ruby, Python, Java เป็นต้น, JSON wire protocol over HTTP เป็นมาตรฐานเปิดที่มีกลไกการขนส่งสำหรับการถ่ายโอนข้อมูลระหว่างไคลเอนต์และเซิร์ฟเวอร์บนเว็บ รองรับโครงสร้างข้อมูลต่างๆ เช่น อาร์เรย์และอ็อบเจ็กต์ ซึ่งทำให้อ่านและเขียนข้อมูลจาก JSON ได้ง่ายขึ้น, Browser Drivers ไดรเวอร์เฉพาะสำหรับแต่ละเบราว์เซอร์และโดยไม่เปิดเผยตรรกะภายในของการทำงานของเบราว์เซอร์ ไดรเวอร์ของเบราว์เซอร์จะโต้ตอบกับเบราว์เซอร์ที่เกี่ยวข้องโดยสร้างการเชื่อมต่อที่ปลอดภัย ไดรเวอร์เบราว์เซอร์เหล่านี้มีความเฉพาะเจาะจงสำหรับภาษาที่ใช้สำหรับกรณีทดสอบอัตโนมัติ เช่นC# , Python , Java เป็นต้น, Browsers ให้การสนับสนุนเบราว์เซอร์หลายตัว เช่น Chrome, Firefox, Safari, Internet Explorer เป็นต้น | compatibility, flexibility, responsibility | https://www.browserstack.com/guide/selenium-webdriver-tutorial#:~:text=Selenium%20WebDriver%20is%20a%20web,language%20to%20create%20test%20scripts. |
---
### *3. Joomla*

| Software | Purpose | Architectural patterns/styles | Quality Attribute | Resource |
| ----------- | ----------- | ----------| ----------|----------|
| Joomla | เพื่อจัดการเนื้อหาแบบโอเพ่นซอร์ส (CMS) ซึ่งใช้ในการสร้างเว็บไซต์และแอปพลิเคชันออนไลน์ | ประกอบด้วยองค์ประกอบหลักเจ็ดส่วน คือ Database, Joomla Framework, Components, Modules, Plugin, Templates, Web Server | compatibility, flexibility, responsibility | https://www.tutorialspoint.com/joomla/joomla_architecture.htm |
---


