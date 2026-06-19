# **🧠 AR Algorithm Game: สนุกกับขั้นตอนในชีวิตประจำวัน**

### **เกม AR (Augmented Reality) เสริมทักษะการคิดเชิงคำนวณและอัลกอริทึม สำหรับวิชาวิทยาการคำนวณ**

\!

เกมเว็บแอปพลิเคชันแบบ **Single-File (HTML/CSS/JS)** ที่ใช้เทคโนโลยีการตรวจจับมือและนิ้วมือ (Hand Tracking) ผ่านกล้องเว็บแคมด้วยไลบรารี **MediaPipe Hands** ร่วมกับหน้าจออินเตอร์เฟสสไตล์โปร่งแสงล้ำสมัย (Glassmorphic 2.5D) เพื่อช่วยให้ผู้เรียนเข้าใจเรื่อง "อัลกอริทึมและการแก้ไขปัญหาในชีวิตประจำวัน" ได้อย่างสนุกสนานและเห็นภาพจริง

## **🌟 จุดเด่นของโปรเจกต์ (Key Features)**

* **AR Hand Tracking Control:** ควบคุมเกมได้ด้วยมือเปล่าผ่านกล้องเว็บแคม โดยใช้ปลายนิ้วชี้เป็นเคอร์เซอร์ และใช้การ **"จีบนิ้ว" (Pinch Gesture)** เพื่อหยิบจับการ์ดขั้นตอนไปเรียงลำดับ  
* **100% Keyboard/Mouse Fallback:** หากกล้องเว็บแคมขัดข้อง หรือผู้ใช้งานไม่มีกล้อง ระบบจะทำการสลับไปให้ผู้เล่นสามารถใช้ **เมาส์ (Mouse Drag & Drop)** หรือ **การสัมผัส (Touch Screen)** ในการเล่นแทนได้โดยอัตโนมัติทันที  
* **Smooth Render Loop:** แยกส่วนประมวลผลวิดีโอ/ตรวจจับมือ ออกจากส่วนแสดงผลกราฟิก (Draw Canvas) อย่างอิสระ โดยใช้ requestAnimationFrame เพื่อการันตีการรันภาพที่ลื่นไหลระดับ 60 FPS  
* **Interactive Cursor Feedback:** แสดงผลสถานะความแม่นยำของเคอร์เซอร์ 4 สี 4 รูปแบบ (ปกติ \= ฟ้า, เล็งเป้า \= เหลืองเส้นประ, จีบไม่โดนเป้า \= แดง, จับสำเร็จ \= เขียวพร้อมเครื่องหมาย ✔️)  
* **EdTech 2.5D Glassmorphism Art:** กราฟิกหน้าต่างควบคุมแบบโปร่งใสและการ์ดคำศัพท์ 2.5D ขนาดใหญ่สีสันสดใส เหมาะสำหรับดึงดูดความสนใจของผู้เรียนระดับประถมและมัธยมต้น

## **🎮 ข้อมูลด่านและเนื้อหาการเรียนรู้ (Level Data & Pedagogy)**

ตัวเกมมีทั้งหมด 5 ด่านหลัก โดยจำลองสถานการณ์ในชีวิตประจำวันเพื่อฝึกทักษะการเรียงลำดับขั้นตอน (Ordering Algorithm):

| ด่านที่ | หัวข้อ (Topic) | ตัวอย่างขั้นตอนที่ต้องเรียงให้ถูกต้อง (Algorithm Steps) |
| :---- | :---- | :---- |
| **1** | **การตื่นนอน** | ตื่นนอน 🥱 ➔ พับผ้าห่ม 🛏️ ➔ เข้าห้องน้ำ 🚿 |
| **2** | **การแปรงฟัน** | หยิบแปรง 🪥 ➔ บีบยาสีฟัน 🧴 ➔ แปรงฟัน 😬 ➔ บ้วนปาก 💧 |
| **3** | **ทำความสะอาดบ้าน** | เก็บของ 🧸 ➔ กวาดบ้าน 🧹 ➔ ถูบ้าน 🪣 |
| **4** | **การอ่านหนังสือ** | เปิดไฟ 💡 ➔ หยิบหนังสือ 📚 ➔ เปิดอ่าน 📖 |
| **5** | **การซักผ้า** | แยกผ้า 🧺 ➔ ใส่เครื่อง 🫧 ➔ ตากผ้า ☀️ |

*เมื่อผ่านครบทั้ง 5 ด่าน ระบบจะแสดงคะแนนเต็ม 500 คะแนน และขึ้นสถานะ "All Clear\!"*

## **🛠️ เทคโนโลยีที่เลือกใช้ (Tech Stack)**

* **Frontend HTML5:** โครงสร้างเว็บพื้นฐาน รันได้ทุกเบราว์เซอร์โดยไม่ต้องติดตั้งโปรแกรมเพิ่ม  
* **Tailwind CSS (via CDN):** ออกแบบเลย์เอาต์ที่ยืดหยุ่น (Responsive Design) รองรับทุกขนาดหน้าจอ และทำ Glassmorphism Style  
* **MediaPipe Hands SDK (via CDN):** เฟรมเวิร์กปัญญาประดิษฐ์จาก Google สำหรับตรวจจับและประมวลผลข้อต่อนิ้วมือแบบ Real-time  
* **Vanilla JavaScript:** ควบคุมตรรกะของเกม (Game Loop), ระบบตรวจจับการชน (Collision Detection), และระบบ Snap-to-Zone

## **🚀 วิธีการเข้าเล่นเกม (How to Run & Play)**

### **ข้อกำหนดก่อนเริ่มใช้งาน (Prerequisites)**

1. คอมพิวเตอร์ หรือ อุปกรณ์เคลื่อนที่ที่มี **กล้องหน้า / เว็บแคม**  
2. เชื่อมต่ออินเทอร์เน็ต (เพื่อโหลดไลบรารี Tailwind CSS และ MediaPipe ผ่าน CDN)  
3. เว็บบราวเซอร์ที่รองรับ (แนะนำอย่างยิ่ง: **Google Chrome** หรือ **Microsoft Edge**)

### **ขั้นตอนการรันโปรเจกต์**

1. ดาวน์โหลดหรือคัดลอกโค้ดจากไฟล์ index.html  
2. บันทึกโค้ดลงในคอมพิวเตอร์ของคุณเป็นไฟล์ชื่อ index.html  
3. ดับเบิ้ลคลิกเพื่อเปิดไฟล์ index.html บนบราวเซอร์ของคุณ  
4. ยอมรับสิทธิ์การขอเข้าถึงกล้องถ่ายรูป (Camera Access Permission)  
5. สนุกกับเกมได้ทันที\!

## **🤏 คู่มือการใช้ท่าทางมือในระบบ AR (AR Gesture Guide)**

* **ขยับเคอร์เซอร์:** ชูมือขึ้นมาหน้ากล้อง ขยับปลายนิ้วชี้ (Index Finger Tip) เพื่อเลื่อนวงกลมสีฟ้าไปยังตำแหน่งที่ต้องการ  
* **หยิบการ์ด / กดปุ่ม:** นำปลายนิ้วชี้ไปวางทับตัวการ์ดหรือปุ่ม จากนั้นทำท่า **"จีบนิ้ว"** (แตะนิ้วโป้งกับนิ้วชี้เข้าหากัน 🤏)  
* **ลากและปล่อย:** ขณะที่ยังจีบนิ้วค้างไว้ ให้ลากการ์ดไปยังช่องวางที่ต้องการด้านล่าง จากนั้น **"กางนิ้วออก"** เพื่อปล่อยการ์ดลงกล่องตอบ

*หมายเหตุ: ในกรณีที่ผู้ใช้สวมเสื้อผ้าโทนสีกลมกลืนกับพื้นหลัง หรือสภาพแสงสว่างไม่เพียงพอ สามารถสลับมาใช้เมาส์หรือนิ้วสัมผัสบนจอแทนได้ตลอดเวลา*

## **📝 หลักการทำงานทางคณิตศาสตร์ที่สำคัญ**

ระบบประมวลผลระยะห่างเพื่อจำลองการทำท่า **"จีบนิ้ว (Pinch)"** ใช้สูตรพีทาโกรัสในการหาระยะห่างแบบ 2 มิติ ระหว่างจุดปลายนิ้วโป้ง (Thumb Tip \- Landmark 4\) และปลายนิ้วชี้ (Index Finger Tip \- Landmark 8\) ของ MediaPipe:

![][image1]หากค่าระยะห่างนี้มีค่าน้อยกว่าระดับความกว้างที่กำหนด (Threshold) ระบบจะตีความว่าผู้เล่นทำการ "จีบนิ้ว/คลิกจับ" โดยอัตโนมัติ

## **🏫 ประโยชน์ทางการศึกษา (Learning Outcomes)**

1. **Decomposition (การย่อยปัญหา):** ผู้เรียนฝึกแตกกระบวนการใหญ่ในชีวิตประจำวันให้ออกมาเป็นขั้นตอนย่อย ๆ  
2. **Algorithm Design (การออกแบบขั้นตอนวิธี):** ผู้เรียนเรียนรู้วิธีการจัดเรียงลำดับตรรกะและเหตุการณ์อย่างเป็นระบบ เพื่อไม่ให้เกิดข้อผิดพลาดในการทำงาน (Bug)  
3. **Active Learning through AR:** กระตุ้นความสนใจของผู้เรียนผ่านนวัตกรรมการสวมบทบาทและการใช้ระบบสัมผัสจากเทคโนโลยีความเป็นจริงเสริม

[image1]: <data:image/png;base64,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>