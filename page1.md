# I2C

| A4/SDA | Digital | พินอินพุตอนาล็อกช่อง 4 / สายข้อมูล I2C (SDA) |
| A5/SCL | Digital | พินอินพุตอนาล็อกช่อง 5 / สายสัญญาณนาฬิกา I2C (SCL) |

# KY-038

DO → D10

KY-038 Sound Sensor Module
เซนเซอร์ตรวจจับเสียง ใช้ไมโครโฟนในการรับสัญญาณเสียง
และส่งสัญญาณออกทาง Digital Output เมื่อมีเสียง
ตามระดับความไวที่กำหนด

VCC → 5V
GND → GND
DO → D10
AO → A0 (สำหรับอ่านค่าระดับเสียงแบบ Analog)

# LCD 16x2

A4 → I2C SDA
A5 → I2C SCL
Address LCD → 0x27
