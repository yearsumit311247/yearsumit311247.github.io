## 2. Session

*English (Source 1 - MDN Web Docs)*
“The most common model for session management is centralized session management, in which the user's session state is stored in the server.”

*English (Source 2 - PHP Manual)*
“Session support in PHP consists of a way to preserve certain data across subsequent accesses. A visitor accessing your web site is assigned a unique id, the so-called session id.”

*Thai*
Session คือกลไกในการจัดการข้อมูลของผู้ใช้งาน โดยข้อมูลสถานะ (Session State) จะถูกจัดเก็บไว้บนเซิร์ฟเวอร์ และเมื่อผู้ใช้เข้าใช้งานเว็บไซต์ ระบบจะกำหนดรหัสประจำตัวที่ไม่ซ้ำกัน (Session ID) ให้กับผู้ใช้แต่ละคน เพื่อใช้เก็บและเรียกคืนข้อมูลระหว่างการเข้าถึงเว็บไซต์ในครั้งถัดไป ทำให้เว็บไซต์สามารถจดจำสถานะของผู้ใช้งานได้จนกว่าจะสิ้นสุดเซสชัน

> “Session เป็นกลไกสำคัญในการพัฒนาเว็บไซต์ เนื่องจากโปรโตคอล HTTP ไม่สามารถจดจำสถานะของผู้ใช้งานได้เอง จึงต้องอาศัย Session ในการเก็บข้อมูล เช่น การเข้าสู่ระบบ สิทธิ์การใช้งาน หรือข้อมูลชั่วคราวต่าง ๆ เพื่อให้ผู้ใช้สามารถใช้งานเว็บไซต์ได้อย่างต่อเนื่อง” (ChatGPT 5.5)

> “Session มักทำงานร่วมกับ Cookie โดย Cookie จะเก็บเฉพาะ Session ID ส่วนข้อมูลจริงจะถูกจัดเก็บไว้บนเซิร์ฟเวอร์ จึงช่วยเพิ่มความปลอดภัยในการจัดการข้อมูลผู้ใช้งาน และเป็นเทคนิคที่นิยมใช้ในระบบเว็บสมัยใหม่” (Google Gemini)

### *🔗 Sources*

* [MDN Web Docs - Session Management](https://developer.mozilla.org/en-US/docs/Web/Security/Authentication/Session_management)
* [PHP Manual - Sessions](https://www.php.net/manual/en/book.session.php)
