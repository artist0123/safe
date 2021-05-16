# [Microcontroller Project FACE BOX กล่องปลดล็อกด้วยใบหน้า](https://artist0123.github.io/facebox)

ในปัจจุบันผู้คนให้ความสำคัญกับความปลอดภัย ความเป็นส่วนตัวและความสะดวกสบายมากขึ้นเรื่อยๆ โดยเฉพาะความปลอดภัยเกี่ยวกับสิ่งของเครื่องใช้ส่วนตัวของตนเอง การรักษาความปลอดภัยด้วยกุญแจจึงเป็นทางออกหนึ่ง โดยปกติกล่องเก็บของจะใช้กุญแจเพื่อปลดล็อก แต่การใช้กุญแจก็มีข้อเสีย เช่น ผู้ใช้ทำกุญแจหายทำให้เปิดกล่องไม่ได้ เราเลยได้คิดค้นสิ่งที่จะทำขึ้นมา มันเริ่มจากการที่อยากทำหัวข้อที่เกี่ยวกับ Microcontroller กับความปลอดภัยที่ประหยัดพิ้นที่ในการทำ ก็เลยได้ออกมาป็นกล่องเก็บของสแกนใบหน้าขนาดย่อม แต่ขนาดย่อมเป็นเพียงแค่แบบทดสอบของโครงงานเท่านั้น ในการนำไปใช้จริงก็สามารถออกแบบในเรื่องของกล่องที่จะใช้และเก็บรายละเอียดของกล่องให้เรียบร้อยน่าใช้มากขึ้น

### ระหว่างการทำงาน

ในระหว่างที่วางแผนในการทำเรียบร้อยแล้ว ในกลุ่มก็จัดแบ่งหน้าที่กันในแต่ละส่วนๆไป ซึ่งการทำโปรเจค Microcontroller ก็ค่อนข้างมีอุปสรรคอยู่บ้าง เช่น การออกไปหาซื้อของมาเพื่อทำ ด้วยความไม่รู้ว่าแถวสถาบันก็มีร้านเกี่ยวกับจำพวกนี้ขายอยู่ในบริเวณ (ไม่ทันคิด) ก็เลยต้องออกไปหาซื้อซะไกลเลย บางส่วนก็สั่งจากในเน็ตมาไว้ก่อนหน้าแล้ว แต่ที่เดินหานั่นคือ **ลืม** พอได้ของครบแล้วก็นัดกันมาทำด้วยเครื่องมือที่ครบครัน เริ่มด้วยการถอดสลักล็อกกล่องอันเก่าออก เพื่อนำกลอนไฟฟ้ามาใส่ แล้วก็ต่อบอร์ดให้เสร็จสรรพเรียบร้อย แต่แล้วก็เกิดปัญหาขึ้นจนได้ นั่นก็คือ **กล้องของ ESP32 CAM ไม่ทำงาน** ก็เป็นสิ่งที่เกิดขึ้นแบบไม่คาดคิดและเรานึกว่าที่กล้องไม่สามารถเปิดขึ้นมาได้เนี่ยจะเป็นจากโค้ดที่เราใช้ แต่แก้ไขไปมา ก็เริ่มตะหงิดใจว่ามันเสียหรือเปล่า ก็เลยจำใจออกไปซื้อเจ้าตัวนี้มาใหม่อีกครั้งหนึ่ง แต่! ราคาค่อนข้างสูง พอนำมาใส่ก็......ติดครับ ตอนนั้นก็ทำให้เรารู้เลยว่าที่เราสั่งมานั้นเป็นของที่ไม่มีคุณภาพเอาซะเลย หรือว่าเจอแจ็คพ็อต? แต่ในวันนั้นก็ผ่านไปได้ด้วยดีแล้วจบด้วยแยกย้ายกลับบ้านนั่นเอง

### อุปกรณ์ที่ใช้ในการทำงานครั้งนี้

ESP32 CAM  1ea
 
FTDI  1ea

Relay 12V 1ea

กลอนไฟฟ้า 1ea

กล่องที่มีฝาเปิด 1ea

รางถ่าน 1.5V แบบ4ก้อน  2ea

Breadboard 1ea

สายจัมพ์ 1มัด

### การทำงานของ FACE BOX

เจ้ากล่องตัวนี้จะมีการทำงานโดยใช้ใบหน้าเพื่อปลดล็อคกลอนไฟฟ้า ก่อนที่จะใช้งานกล่องตัวนี้จะต้องมีการลงทะเบียนใบหน้าของเราก่อน เพื่อที่จะให้เจ้าตัว ESP32 CAM ตรวจสอบใบหน้าที่ถูกต้อง

**สุดท้ายนี้ขอฝาก github.io เพื่อเข้าไปชมรายละเอียดเพิ่มเติมได้เลยครับ [Click](https://artist0123.github.io/facebox)**

<img src="https://i.imgur.com/8UB8H79.png" width="1000" height="1300">
