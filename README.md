# After-School Kickers / แข้งน้อยหลังเลิกเรียน

A small 4-a-side schoolyard football game for touch screens. It runs in Safari on an iPad (tested target: iPad 6) and in any desktop browser.

เกมเตะบอล 4 ต่อ 4 ที่สนามโรงเรียน เล่นบนจอสัมผัสผ่าน Safari บน iPad หรือเบราว์เซอร์บนคอมก็ได้

**Play / เล่นเกม:** https://cmku-dft.github.io/school-football-game/

## How to play / วิธีเล่น

| Touch control | English | ไทย |
|---|---|---|
| Left thumb | Drag anywhere to run | ลากเพื่อวิ่ง |
| Run (hold) | Sprint; it drains stamina, and at zero you are tired and slow | วิ่งเร็ว แต่เหนื่อยได้ |
| Shoot / Tackle | Hold to shoot harder; without the ball, lunge for it | ยิง หรือพุ่งแย่ง |
| Pass / Switch | Pass to a friend; when the other team has the ball, switch to the friend nearest it | ส่ง หรือสลับตัว |
| Dodge | Spin as a defender tackles and they fall over | หมุนตัวหลบ |

**Special meter.** Completed passes, tackles and dodges fill the meter. When it is full, Wen's next shot is a Fire Shot (straight and very fast) and Mei's is a Curve Shot (bends around the keeper).

**Switch players** can be turned off on the title screen; then you always control Wen or Mei.

### Keyboard and mouse / คีย์บอร์ดและเมาส์

| Input | Action |
|---|---|
| W A S D or arrow keys | Run / วิ่ง |
| Shift (hold) | Sprint / วิ่งเร็ว |
| Left click (hold) or Space / J | Shoot toward the pointer; without the ball, tackle / ยิง หรือแย่ง |
| Right click or K / X / E | Pass, call for the ball, or switch player / ส่ง ขอบอล หรือสลับตัว |
| Q or F | Dodge / หลบ |
| Tab or R | Switch player / สลับตัว |
| P or Esc | Pause / หยุดพัก |
| L (on menus) | Switch language / เปลี่ยนภาษา |

On the title screen, pick Wen or Mei, then press Kick off.

Each match lasts 90 seconds. A draw goes to next-goal-wins.

## The season / ฤดูกาลแข่งขัน

You play for class 4/3 and face the 13 other classes in order. Progress is saved on the device.

| Grade | Classes | How they play |
|---|---|---|
| 4 | 4/1, 4/2, 4/4 to 4/7 | Fast runners with wild shooting |
| 5 | 5/1 to 5/4 | Short passers who work the ball close |
| 6 | 6/3, 6/2, 6/1 | Big kids; bumping into them knocks you over |

Every class has its own named players and a captain with a special move: Lightning Dash, Spin Dodge, Banana Shot, Rocket Shot or Bulldozer. The screen before each match shows the captain and a tip for beating the move. Losing a match makes the rematch slightly easier.

The language button in the top-right corner of the title screen switches between English and Thai.

## Technical notes

- One file: `index.html` (plain HTML5 canvas and Web Audio, no build step, no dependencies apart from one Google Font).
- The game must be opened from a web address. Opening the `.html` file directly from the iPad Files app shows a preview that does not run scripts.
