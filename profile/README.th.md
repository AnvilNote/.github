# AnvilNote

**Languages:** [繁體中文](README.zh-TW.md) | [English](README.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | **ไทย** | [Русский](README.ru.md)

[![Release](https://img.shields.io/github/v/release/AnvilNote/anvilnote-desktop?style=for-the-badge&label=Release&color=black)](https://github.com/AnvilNote/anvilnote-desktop/releases/latest)
[![Downloads](https://img.shields.io/badge/Downloads-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple-black?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20AppImage-black?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Electron](https://img.shields.io/badge/Electron-Desktop-black?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)

AnvilNote คือแอปเขียนบันทึกแบบออฟไลน์เป็นหลัก (offline-first) ออกแบบมาสำหรับบันทึกยาว เอกสารประกอบการบรรยาย รายงาน และเอกสารทางวิชาการ

แอปนี้ให้ประสบการณ์การเขียนคล้าย Notion แต่เน้นไปที่การส่งออกเอกสารแบบมีโครงสร้าง เทมเพลต ฟอนต์ สูตรคณิตศาสตร์ บล็อกโค้ด และการสร้างไฟล์ PDF มากกว่า

## ทำไมต้อง AnvilNote

- **ออฟไลน์เป็นค่าเริ่มต้น** ข้อมูลบันทึกของคุณอยู่บนเครื่องของคุณเอง ไม่จำเป็นต้องเชื่อมต่ออินเทอร์เน็ตตลอดเวลา
- **ไม่ต้องเข้าสู่ระบบสำหรับการใช้งานเดสก์ท็อปแบบโลคัล** เปิดแอปแล้วเริ่มเขียนได้ทันที
- **ออกแบบมาเพื่อการเขียนบทความยาวและเอกสารที่มีโครงสร้าง** ไม่ใช่แค่บันทึกสั้น ๆ แต่รวมถึงบันทึกการบรรยาย รายงาน และงานวิชาการ
- **สูตรคณิตศาสตร์ บล็อกโค้ด เทมเพลต และการส่งออก PDF** เป็นฟีเจอร์หลัก ไม่ใช่ของแถม
- **ใช้ Typst เป็นแกนหลักในการเรนเดอร์เอกสาร** ให้ผลลัพธ์ PDF ที่รวดเร็วและคุณภาพสูง
- **แอปเดสก์ท็อปมาพร้อมเครื่องมือที่จำเป็นในตัว** ผู้ใช้ไม่ต้องติดตั้ง Node.js หรือ Typst แยกต่างหาก

## รีพอสิทอรี

AnvilNote ประกอบด้วยหลายรีพอสิทอรี ไม่ใช่ monorepo เดียว

| รีพอสิทอรี | วัตถุประสงค์ | สถานะ |
| --- | --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | ภาพรวมโปรเจกต์ เอกสาร สถาปัตยกรรม แผนงาน และคู่มือการ build จาก source | วางแผนไว้ |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | เอดิเตอร์ UI เอกสาร การเลือกเทมเพลต และส่วนติดต่อผู้ใช้บนเว็บ | วางแผนไว้ / ภายใน |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | API แบบโลคัล ฐานข้อมูล SQLite การจัดเก็บเอกสาร และ endpoint สำหรับส่งออก | วางแผนไว้ / ภายใน |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | การเรนเดอร์ PDF ด้วย Typst เทมเพลต ฟอนต์ และการคอมไพล์เอกสาร | วางแผนไว้ / ภายใน |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | กระบวนการส่งออกไฟล์ DOCX | วางแผนไว้ / ภายใน |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | เชลล์เดสก์ท็อป Electron, sidecar ที่มากับแอป, การแพ็กเกจ, ตัวติดตั้ง และการ build เพื่อเผยแพร่ | พรีวิวสาธารณะ |

## ดาวน์โหลด

แอปเดสก์ท็อปดาวน์โหลดได้ที่:

**https://github.com/AnvilNote/anvilnote-desktop/releases**

## สถานะปัจจุบัน

AnvilNote อยู่ในช่วงพัฒนาระยะแรก รีพอสิทอรีบางส่วนด้านบนยังเป็นแบบภายในหรือยังไม่เปิดเผยต่อสาธารณะ ขณะที่ฟังก์ชันหลักกำลังถูกพัฒนาอยู่ แอปเดสก์ท็อปอยู่ในช่วงพรีวิวสาธารณะแล้ว ส่วนรีพอสิทอรีอื่น ๆ จะทยอยเปิดเผยเมื่อมีความเสถียรเพียงพอที่จะรองรับผู้ร่วมพัฒนาจากภายนอก

## การมีส่วนร่วม

เมื่อ [AnvilNote/anvilnote](https://github.com/AnvilNote/anvilnote) เปิดเผยต่อสาธารณะแล้ว ให้เริ่มต้นที่นั่นเพื่อดูภาพรวมโปรเจกต์ สถาปัตยกรรม และแนวทางการมีส่วนร่วม

ปัญหาเกี่ยวกับการแพ็กเกจ ตัวติดตั้ง และการเผยแพร่เวอร์ชันเดสก์ท็อป ให้แจ้งที่ [AnvilNote/anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop)

ดูแนวทางการมีส่วนร่วมทั้งองค์กรฉบับเต็มได้ที่ [CONTRIBUTING.md](https://github.com/AnvilNote/.github/blob/main/CONTRIBUTING.md) ในรีพอสิทอรี `.github`
