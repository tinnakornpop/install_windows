# Check Key Windows
## Check for Command
- กดปุ่ม `Windows` + `R`
- พิมพ์ `cmd` + `Enter`
- รันคำสั่งในหน้า Command Prompt ตามนี้
```
wmic path softwarelicensingservice get OA3xOriginalProductKey
```
✅ หากคอมพิวเตอร์ของเรามี OEM License ก็จะแสดง Product Key ขึ้นมา  
❌ หากว่า Product Key นั้นไม่แสดงขึ้นมา นั้นหมายความว่า OEM Product Key ของคุณนั้น ถูกลบออกไปจาก Motherboard แล้วครับ ทางเราแนะนำให้คุณทำการติดต่อ OEM (Original Equipment Manufacturer) หรือผู้ผลิตเท่านั้นครับ

## Check for Program
- Download: <a href="https://software.thaiware.com/14600-ShowKeyPlus-Download.html">ShowKeyPlus</a>
