# Check Key Windows
1. กดปุ่ม `Windows` + `R`
2. พิมพ์ `cmd` + `Enter`
3. รันคำสั่งในหน้า Command Prompt ตามนี้
```
wmic path softwarelicensingservice get OA3xOriginalProductKey
```
4. หากคอมพิวเตอร์ของเรามี OEM License ก็จะแสดง Product Key ขึ้นมา
