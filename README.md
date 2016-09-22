# responsive-design
Just a note of basic responsive design

# Viewport คืออะไร?
เป็นส่วนที่เราสามารถมองเห็นได้ เป็นอันดับแรกที่เป็นเวปไซต์ จะมองเป็น visibility area ก็ได้

# Viewport ไม่ใช่มาตรฐานที่ดี
viewport meta tag นี้ ไม่ใช่มารฐานกลางด้วยซำ Apple คิดขึ้นมา เพื่อตอบสนอง Safari บน iOS

# การใช้งาน

## ขนาดของหน้าขอ width มีผลเท่ากับ device ที่ใช้งานอยู่ในขณะนั้น
```
<meta name="viewport" content="width=device-width">
```

## เมื่อเปิดเพจ เราไม่อยากให้ Browser zoom อัตโนมัติ
```
<meta name="viewport" content="initial-scale=1">
```

## จำกัดระยะ zoom
```
<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=0.5, maximum-scale=1">
```

## ไม่ให้ User zoom เลยก็ใช้
```
<meta name="viewport" content="initial-scale=1.0, user-scalable=no">
```
