# Check Key Windows
1. กดปุ่ม `Windows` + `R`
2. พิมพ์ `cmd` + `Enter`
3. รันคำสั่งในหน้า Command Prompt ตามนี้
```
wmic path softwarelicensingservice get OA3xOriginalProductKey
```
4. หากคอมพิวเตอร์ของเรามี OEM License ก็จะแสดง Product Key ขึ้นมา


# Download Windows
- ดาวน์โหลด Windows ที่ต้องการ
  - <a href="https://www.microsoft.com/en-gb/software-download/windows10">Windows 10</a>: Create Windows 10 installation media >> `Download tool now`
  - <a href="https://www.microsoft.com/en-gb/software-download/windows11">Windows 11</a>: Create Windows 11 Installation Media >> `Download Now`

## Create ISO to USB
- คลิก `Accept`
- คลิก `Next` (หากต้องการ Windows ภาษาไทย ให้ติ๊ก ✅ ออก แล้วเลือกภาษาไทยที่แท็บ Language)
- เลือก `USB Flash Drive`
- คลิก `Next`
- รอดาวน์โหลดไฟล์ลง USB จนเสร็จ แล้วคลิก `Finish`

## Create ISO to PC
- คลิก `Accept`
- คลิก `Next` (หากต้องการ Windows ภาษาไทย ให้ติ๊ก ✅ ออก แล้วเลือกภาษาไทยที่แท็บ Language)
- เลือก `ISO file`
- คลิก `Next`
- รอดาวน์โหลดไฟล์ลง PC จนเสร็จ แล้วคลิก `Finish`


# Install Windows
Boot to `USB Flash Drive`

## หน้า Windows Setup
- Language to install: `English (United States)` (Default)
- Time and currency format: `เลือกตามประเทศที่อาศัย`
- Keyboard or input method: `US` (Default)
- คลิก `Next`
- คลิก `Install now` (Setup is starting)
