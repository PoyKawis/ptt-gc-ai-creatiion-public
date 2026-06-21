# Module 3: Hardening and Deployment Preparation

หน้านี้เป็นสารบัญของแบบฝึกหัดทั้งหมดใน Module 3 โดยต่อยอดจาก **Financial Report Assistant** ที่สร้างและทดสอบเบื้องต้นใน Module 2 เพื่อทำให้ Agent ตอบได้ชัดเจน ปลอดภัย และพร้อมสำหรับการนำไปสาธิตหรือทดสอบกับผู้ใช้จริง

## ก่อนเริ่ม

ควรทำ [Module 2: Copilot Studio Core Build](../module-2/README.md) ให้เสร็จก่อน โดยเฉพาะการตั้งค่า fallback และ mini test cycle ใน [exercise-6](../module-2/exercise-6-fallback-and-mini-test/README.md) เพราะ Module นี้จะใช้ผลการทดสอบนั้นมาปรับ reliability, ขอบเขตการตอบ และความพร้อมก่อน publish

## Table of Contents

| Exercise | Title | Link |
|---|---|---|
| exercise-1-clarification-and-validation | ถามให้ชัดและยืนยันข้อมูลก่อนวิเคราะห์ | [Open](./exercise-1-clarification-and-validation/README.md) |
| exercise-2-escalation-and-safe-completion | ออกแบบ Escalation และ Safe Completion | [Open](./exercise-2-escalation-and-safe-completion/README.md) |
| exercise-3-hardening-patterns | Hardening Patterns สำหรับ Agent | [Open](./exercise-3-hardening-patterns/README.md) |
| exercise-4-channel-and-publishing | เลือก Channel และ Publish Agent | [Open](./exercise-4-channel-and-publishing/README.md) |
| exercise-5-measurement-mindset | นิยาม Measurement Mindset และ UAT Readiness | [Open](./exercise-5-measurement-mindset/README.md) |

## ลำดับการเรียน

1. เริ่มที่ [exercise-1-clarification-and-validation](./exercise-1-clarification-and-validation/README.md) เพื่อใช้ผลจาก mini test cycle ของ Module 2 ระบุข้อมูลที่ Agent ต้องถามและยืนยันก่อนวิเคราะห์
2. ต่อด้วย [exercise-2-escalation-and-safe-completion](./exercise-2-escalation-and-safe-completion/README.md) เพื่อกำหนดว่าเมื่อไร Agent ควรตอบเอง ถามเพิ่ม หรือส่งต่ออย่างปลอดภัย
3. จากนั้นไปที่ [exercise-3-hardening-patterns](./exercise-3-hardening-patterns/README.md) เพื่อทำให้การตอบอยู่ในขอบเขต มี approval ที่เหมาะสม และรับมือ failure ได้ดีขึ้น
4. เรียน [exercise-4-channel-and-publishing](./exercise-4-channel-and-publishing/README.md) เพื่อเลือก channel, publish และทดสอบ Agent ในบริบทที่ตั้งใจใช้งาน
5. ปิดท้ายด้วย [exercise-5-measurement-mindset](./exercise-5-measurement-mindset/README.md) เพื่อกำหนดสิ่งที่ถือว่าใช้งานได้ดีและเตรียมความพร้อมสำหรับ UAT
