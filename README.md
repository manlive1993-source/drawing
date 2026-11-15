# วาดบนภาพ (PWA)

## วางบน GitHub Pages
1. สร้าง Repository ใหม่บน GitHub (Public) เช่น `photo-draw`
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png) ไว้ที่ root
3. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save
4. รอ 1–2 นาที เปิด `https://<ชื่อผู้ใช้>.github.io/photo-draw/`
5. มือถือ: เมนูเบราว์เซอร์ → "เพิ่มลงหน้าจอโฮม / ติดตั้งแอป"

หมายเหตุ: กล้องสดต้องใช้ HTTPS (GitHub Pages ใช้ได้) · เมื่อแก้โค้ดแล้วเปลี่ยน `V` ใน sw.js เป็น v2, v3...
