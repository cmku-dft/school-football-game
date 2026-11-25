# After-School Kickers / แข้งน้อยหลังเลิกเรียน

A small 4-a-side schoolyard football game for touch screens. It runs in Safari on an iPad (tested target: iPad 6) and in any desktop browser.

เกมเตะบอล 4 ต่อ 4 ที่สนามโรงเรียน เล่นบนจอสัมผัสผ่าน Safari บน iPad หรือเบราว์เซอร์บนคอมก็ได้

**Play / เล่นเกม:** https://cmku-dft.github.io/school-football-game/

## How to play / วิธีเล่น

| Control | English | ไทย |
|---|---|---|
| Left thumb | Drag anywhere to run | ลากเพื่อวิ่ง |
| Shoot | Hold to charge; a full bar is a fire shot | กดค้างให้หลอดเต็มจะได้ลูกยิงไฟ |
| Pass | Pass to a friend, or call for the ball | ส่งให้เพื่อน หรือขอบอล |
| No ball | Shoot becomes Tackle (lunge for the ball) | ปุ่มยิงกลายเป็นแย่งบอล |

Keyboard: arrows or WASD to run, Space or J to shoot, K or X to pass, L to switch language.

Each match lasts 90 seconds. Win to face the next grade (Grade 4, 5, then 6). A draw goes to next-goal-wins.

The language button in the top-right corner of the title screen switches between English and Thai.

## Technical notes

- One file: `index.html` (plain HTML5 canvas and Web Audio, no build step, no dependencies apart from one Google Font).
- The game must be opened from a web address. Opening the `.html` file directly from the iPad Files app shows a preview that does not run scripts.
