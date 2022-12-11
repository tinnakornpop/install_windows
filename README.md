# Check Key Windows
## Check for Command
- กดปุ่ม `Windows` + `R`
- พิมพ์ `cmd` + `Enter`
- รันคำสั่งในหน้า Command Prompt ตามนี้
```
wmic path softwarelicensingservice get OA3xOriginalProductKey
```
✅ หากคอมพิวเตอร์ของเรามี OEM License ก็จะแสดง Product Key ขึ้นมา  
❌ หาก Product Key นั้นไม่แสดงขึ้นมา หมายความว่า OEM Product Key ของเรา ถูกลบออกไปจาก Motherboard แล้ว แนะนำให้ทำการติดต่อ OEM (Original Equipment Manufacturer) หรือผู้ผลิตเท่านั้น

## Check for Program
- Download: <a href="https://software.thaiware.com/14600-ShowKeyPlus-Download.html">ShowKeyPlus</a>
