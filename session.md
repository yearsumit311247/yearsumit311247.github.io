## 2. Session

*English (Source 1 - MDN Web Docs)*

> “The most common model for session management is centralized session management, in which the user's session state is stored in the server.”

*English (Source 2 - PHP Manual)*

> “Session support in PHP consists of a way to preserve certain data across subsequent accesses. A visitor accessing your web site is assigned a unique id, the so-called session id.”

*Thai*
Session คือข้อมูลที่ถูกจัดเก็บไว้บนฝั่งเซิร์ฟเวอร์ (Server) เพื่อใช้จดจำสถานะของผู้ใช้งานแต่ละคน โดยผู้ใช้แต่ละรายจะมี Session ID ที่ไม่ซ้ำกัน ซึ่งมักถูกเก็บไว้ใน Cookie ของเบราว์เซอร์ เมื่อผู้ใช้ส่งคำขอไปยังเว็บไซต์ ระบบจะใช้ Session ID เพื่อเรียกข้อมูล Session ที่เก็บไว้ ทำให้สามารถจดจำการเข้าสู่ระบบและข้อมูลชั่วคราวต่าง ๆ ได้จนกว่าจะหมดอายุหรือผู้ใช้ออกจากระบบ

> “Session เป็นกลไกสำคัญในการพัฒนาเว็บไซต์ เนื่องจากโปรโตคอล HTTP ไม่สามารถจดจำผู้ใช้ระหว่างการร้องขอแต่ละครั้งได้ จึงต้องใช้ Session เพื่อเก็บข้อมูล เช่น สถานะการเข้าสู่ระบบ สิทธิ์การใช้งาน หรือข้อมูลชั่วคราวต่าง ๆ ทำให้ผู้ใช้สามารถใช้งานเว็บไซต์ได้อย่างต่อเนื่อง” (ChatGPT 5.5)

> “Session ทำงานร่วมกับ Cookie โดย Cookie จะเก็บเฉพาะ Session ID ส่วนข้อมูลจริงจะถูกจัดเก็บไว้บนเซิร์ฟเวอร์ จึงช่วยเพิ่มความปลอดภัยในการจัดการข้อมูลผู้ใช้งาน และเป็นเทคนิคที่นิยมใช้ในระบบล็อกอินของเว็บไซต์” (Google Gemini)

### *🔗 Sources*

* https://developer.mozilla.org/en-US/docs/Web/Security/Authentication/Session_management
* https://www.php.net/manual/en/book.session.php
* https://greedisgoods.com/session/
* https://www.borntodev.com/2020/07/10/cookie-vs-session/
