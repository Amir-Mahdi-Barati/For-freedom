# For-freedom
![ESP32](https://img.shields.io/badge/ESP32-ESP32-red)
![Arduino](https://img.shields.io/badge/Arduino-C/C++-00979D)
![LCD](https://img.shields.io/badge/LCD-16x2-yellow)
![Keypad](https://img.shields.io/badge/Keypad-4x3-green)
# ESP32 Timer 



```bash
git clone https://github.com/Amir-Mahdi-Barati/For-freedom
cd Fractal-Tree
```

## توضیحات پروژه
یک تایمر امنیتی مبتنی بر ESP32 با ویژگی‌های:
- تایمر معکوس قابل تنظیم
- ورود رمز برای توقف ایمن
- حالت هشدار در صورت ورود رمز اشتباه
- خروجی رله برای کنترل دستگاه‌ها
- بوق‌ر هشدار
## قطعات مورد نیاز

| قطعه                | تعداد     |
|---------------------|----------|
| ESP32               | 1        |
| LCD 16x2            | 1        |
| کیپد 3x4            | 1        |
| ماژول رله           | 1        |
| بیزر                 | 1        |
| سیم‌بندی / برد بورد | مطابق نیاز |

## اتصالات

| قطعه / دستگاه   | پین ESP32  |
|-----------------|------------|
| LCD RS          | GPIO23     |
| LCD EN          | GPIO22     |
| LCD D4          | GPIO21     |
| LCD D5          | GPIO19     |
| LCD D6          | GPIO18     |
| LCD D7          | GPIO17     |
| LCD VCC         | 3.3V       |
| LCD GND         | GND        |
| کیپد R1         | GPIO13     |
| کیپد R2         | GPIO12     |
| کیپد R3         | GPIO14     |
| کیپد R4         | GPIO27     |
| کیپد C1         | GPIO26     |
| کیپد C2         | GPIO25     |
| کیپد C3         | GPIO33     |
| رله IN          | GPIO32     |
| رله VCC         | 3.3V       |
| رله GND         | GND        |
| بیزر            | GPIO4      |
| بیزر GND        | GND        |

> ⚠️ اگر LCD یا بیزر ۵ ولت هستند، از **Level Shifter** برای پین‌های ESP32 استفاده کنید
>#  رمز = 7355608
