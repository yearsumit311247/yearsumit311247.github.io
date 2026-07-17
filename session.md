## 2. Session

*English (Source 1 - MDN Web Docs)*  
> “A website needs to treat a series of requests from a single client as representing a session.”

*English (Source 2 - PHP Manual)*  
> “Session support in PHP consists of a way to preserve certain data across subsequent accesses.”

*Thai*  
Session คือกลุ่มของการร้องขอ (Requests) จากผู้ใช้งานคนเดียวกันที่เว็บไซต์มองว่าเป็นการใช้งานต่อเนื่อง โดยระบบจะเก็บข้อมูลบางอย่างไว้เพื่อให้สามารถจดจำสถานะของผู้ใช้ระหว่างการเข้าถึงเว็บไซต์หลายครั้งได้

> “Session เป็นกลไกสำคัญในการพัฒนาเว็บไซต์ เนื่องจาก HTTP เป็นโปรโตคอลแบบ Stateless ที่ไม่สามารถจดจำผู้ใช้ระหว่างการร้องขอแต่ละครั้งได้ จึงต้องอาศัย Session ในการเก็บข้อมูล เช่น สถานะการเข้าสู่ระบบ สิทธิ์การใช้งาน และข้อมูลชั่วคราวต่าง ๆ เพื่อให้ผู้ใช้สามารถใช้งานเว็บไซต์ได้อย่างต่อเนื่อง” (ChatGPT 5.5)

> “Session มักทำงานร่วมกับ Cookie โดย Cookie จะเก็บ Session ID ส่วนข้อมูลจริงจะถูกจัดเก็บไว้บนเซิร์ฟเวอร์ ทำให้เว็บไซต์สามารถระบุตัวตนของผู้ใช้งานได้อย่างปลอดภัย และลดความเสี่ยงจากการเก็บข้อมูลสำคัญไว้บนฝั่งผู้ใช้” (Google Gemini)

### *🔗 Sources*

* [MDN Web Docs - Session Management](https://developer.mozilla.org/en-US/docs/Web/Security/Authentication/Session_management)
* [PHP Manual - Sessions](https://www.php.net/manual/en/book.session.php)
