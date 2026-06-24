# Module 3: Hardening and Deployment Preparation

หน้านี้เป็นสารบัญของแบบฝึกหัดทั้งหมดใน Module 3 โดยต่อยอดจาก **Financial Report Assistant** ที่สร้างและทดสอบเบื้องต้นใน Module 2 เพื่อทำให้ Agent ตอบได้ชัดเจน ปลอดภัย และพร้อมสำหรับการนำไปสาธิตหรือทดสอบกับผู้ใช้จริง

## ก่อนเริ่ม

ควรทำ [Module 2: Copilot Studio Core Build](../module-2/README.md) ให้เรียบร้อยก่อน เพื่อให้มีความคุ้นเคยกับการสร้าง Agent และทดสอบเบื้องต้นแล้ว

## Table of Contents

| Exercise | Title | Link |
|---|---|---|
| exercise-1-clarification-and-validation | Reliability Pattern | [Open](./exercise-1-clarification-and-validation/README.md) |
| exercise-2-escalation-and-safe-completion | ออกแบบ Escalation และ Safe Completion | [Open](./exercise-2-escalation-and-safe-completion/README.md) |
| exercise-3-hardening-patterns | Hardening Patterns สำหรับ Agent | [Open](./exercise-3-hardening-patterns/README.md) |
| exercise-4-channel-and-publishing | เลือก Channel และ Publish Agent | [Open](./exercise-4-channel-and-publishing/README.md) |
| exercise-5-measurement-mindset | Measurement Mindset | [Open](./exercise-5-measurement-mindset/README.md) |

## ลำดับการเรียน

1. เริ่มที่ [exercise-1-clarification-and-validation](./exercise-1-clarification-and-validation/README.md) ระบุข้อมูลที่ Agent ต้องถามและยืนยันก่อนวิเคราะห์
2. ต่อด้วย [exercise-2-escalation-and-safe-completion](./exercise-2-escalation-and-safe-completion/README.md) เพื่อกำหนดว่าเมื่อไร Agent ควรตอบเอง ถามเพิ่ม หรือส่งต่ออย่างปลอดภัย
3. จากนั้นไปที่ [exercise-3-hardening-patterns](./exercise-3-hardening-patterns/README.md) เพื่อทำให้การตอบอยู่ในขอบเขต มี approval ที่เหมาะสม และรับมือ failure ได้ดีขึ้น
4. เรียน [exercise-4-channel-and-publishing](./exercise-4-channel-and-publishing/README.md) เพื่อเลือก channel, publish และทดสอบ Agent ที่ตั้งใจใช้งาน
5. ปิดท้ายด้วย [exercise-5-measurement-mindset](./exercise-5-measurement-mindset/README.md) เพื่อกำหนดสิ่งที่ถือว่า Agent สามารถใช้งานได้ดี

## ต่อบทเรียนหลัง Module 3

ถ้าต้องการทบทวน Module 1-3 ในรูปแบบ tutoring session ประมาณ 1.5 ชั่วโมง ให้ไปต่อที่ [Module 3.5: Recap & Tutoring Session](../module-3-5/README.md) เพื่อฝึก Missing Info Detective, Echo Confirmation, Fallback/Escalation, Don't Guess และ Chat-Friendly response ก่อนเข้าสู่ Module 4