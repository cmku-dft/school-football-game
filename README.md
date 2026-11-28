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

A match lasts 2 minutes by default; the Time button beside Kick off switches between 1:30, 2:00, 3:00 and 5:00. A draw goes to next-goal-wins.

## Pitches and weather / สนามและสภาพอากาศ

| Condition | Where in the season | Effect |
|---|---|---|
| Sunny evening | Grade 4 | Normal |
| Blazing sun | 4/7 | Stamina drains faster; a water bottle on the pitch refills it |
| Rain | 5/1, 5/3 | The ball skids, players slide, puddles stop the ball |
| Windy | 5/2, 5/4 | Wind pushes the ball, more so in the air; an arrow shows direction |
| Concrete yard | 6/3, 6/2 | The ball runs fast and bounces hard off the walls |
| Dusk | 6/1 | Floodlights, visual only |

Once you have reached a condition in the season, the Pitch button on the pre-match screen lets you pick it for any match.

## The season / ฤดูกาลแข่งขัน

You play for class 4/3 and face the 13 other classes in order. Progress is saved on the device.

| Grade | Classes | How they play |
|---|---|---|
| 4 | 4/1, 4/2, 4/4 to 4/7 | Fast runners with wild shooting |
| 5 | 5/1 to 5/4 | Short passers who work the ball close |
| 6 | 6/3, 6/2, 6/1 | Big kids; bumping into them knocks you over |

Every class has its own named players and a captain with a special move: Lightning Dash, Spin Dodge, Banana Shot, Rocket Shot or Bulldozer. The screen before each match shows the captain and a tip for beating the move. Losing a match makes the rematch slightly easier.

The language button in the top-right corner of the title screen switches between English and Thai.

## Stars, shop and trophies / ดาว ร้านค้า ถ้วยรางวัล

- Every match has three stars: win the match, plus two side goals shown before kick-off (for example win by two, keep a clean sheet, score with the special shot, complete six passes). Stars are only awarded for a win.
- **Matches** on the title screen lets you replay any class you have reached to collect missing stars.
- **Shop** spends stars on balls, headbands, hairstyles and goal celebrations. There are 39 stars in total, exactly enough to buy everything.
- **Trophies** shows 12 trophies and lifetime stats (goals, wins, best winning streak, passes, dodges and more).
- Everything is saved in the browser's local storage on that device.

## Team, coins and training / จัดทีม เหรียญ ฝึกซ้อม

- **Recruit captains.** Earn all three stars against a class and its captain joins your squad. On the Team screen you choose who plays defender and midfielder. Recruited captains keep their move: as teammates they use it on their own, and when you control one, shooters (Rocket, Banana) fire it with a full special meter while the others give a passive bonus (faster sprint, quicker dodge, knocking rivals over while sprinting).
- **Coins.** Every match pays coins for goals, passes, tackles, dodges and winning. Coins can be earned again and again, unlike stars.
- **Special shots.** Coins buy Zigzag, Split and Smash shots; one is in use at a time in place of the default Fire or Curve shot.
- **Training.** Coins raise your main player's speed, stamina and shot power, three levels each.

## Technical notes

- One file: `index.html` (plain HTML5 canvas and Web Audio, no build step, no dependencies apart from one Google Font).
- The game must be opened from a web address. Opening the `.html` file directly from the iPad Files app shows a preview that does not run scripts.
