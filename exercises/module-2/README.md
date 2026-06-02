# Module 2: Copilot Studio Core Build

หน้านี้เป็นสารบัญของแบบฝึกหัดทั้งหมดใน Module 2 โดยเน้นการค่อยๆ เพิ่ม **Nodes** ให้ **Topic เดียวกัน** สำหรับกระบวนงานจริง เช่นงานสรุปรายงานการเงินรายเดือน

## Support Files

- [Finance dataset workbook](../../files/module-2/CPALL-Monthly-Financial-Report-May2026.xlsx)
- [Dataset guide](../../files/module-2/README.md)

## Table of Contents

| Exercise | Title | Link |
|---|---|---|
| exercise-1-create-financial-agent | สร้าง Financial Report Assistant Agent | [Open](./exercise-1-create-financial-agent/README.md) |
| exercise-2-topic-intake-flow | ออกแบบ Topic รับความต้องการรายงานการเงิน | [Open](./exercise-2-topic-intake-flow/README.md) |
| exercise-3-excel-analysis-action | เชื่อมข้อมูล Excel และเรียก Action วิเคราะห์ | [Open](./exercise-3-excel-analysis-action/README.md) |
| exercise-4-draft-and-revision-loop | สร้าง Draft และ Revision Loop | [Open](./exercise-4-draft-and-revision-loop/README.md) |
| exercise-5-hybrid-topic-with-generative | ทำ Hybrid Topic: Structured + Generative | [Open](./exercise-5-hybrid-topic-with-generative/README.md) |
| exercise-6-fallback-and-mini-test | ออกแบบ Fallback และ Mini Test Cycle | [Open](./exercise-6-fallback-and-mini-test/README.md) |

## ลำดับการเรียน

1. เริ่มที่ [exercise-1-create-financial-agent](./exercise-1-create-financial-agent/README.md) เพื่อสร้าง Agent ตั้งต้นและ instructions สำหรับ Financial Report Assistant
2. ต่อด้วย [exercise-2-topic-intake-flow](./exercise-2-topic-intake-flow/README.md) เพื่อวางโครง Topic และตัวแปรหลักของ Topic เดียวกัน
3. จากนั้นไปที่ [exercise-3-excel-analysis-action](./exercise-3-excel-analysis-action/README.md) เพื่อเพิ่ม node สำหรับเชื่อมข้อมูลและวิเคราะห์ต่อจาก Topic เดิม
4. เรียน [exercise-4-draft-and-revision-loop](./exercise-4-draft-and-revision-loop/README.md) เพื่อเติม revision loop ลงใน Topic เดิม
5. ต่อด้วย [exercise-5-hybrid-topic-with-generative](./exercise-5-hybrid-topic-with-generative/README.md) เพื่อขยาย Topic เดิมให้รองรับทั้ง structured flow และ generative answers
6. ปิดท้ายด้วย [exercise-6-fallback-and-mini-test](./exercise-6-fallback-and-mini-test/README.md) เพื่อ harden Topic เดิมด้วย fallback, escalation, และการทดสอบทั้งระบบ