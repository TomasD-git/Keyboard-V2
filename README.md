# Keyboard-V2
**small, compact keyboard for everyday use.**
<img width="1197" height="705" alt="Screenshot 2026-04-11 211753" src="https://github.com/user-attachments/assets/f20de9b2-a44a-4ada-bf85-db1aa76dd3aa" />

## Layout

```
["Esc","1","2","3","4","5","6","7","8","9","0","-","=",{w:2},"Backspace"],
[{w:1.5},"Tab","Q","W","E","R","T","Y","U","I","O","P","[","]",{w:1.5},"\\"],
[{w:1.75},"Caps","A","S","D","F","G","H","J","K","L",";","'",{w:2.25},"Enter"],
[{w:2.25},"Shift","Z","X","C","V","B","N","M",",",".","/",{w:2.75},"Shift"],
[{w:1.25},"Ctrl",{w:1.25},"Win",{w:1.25},"Alt",{w:6.25},"Space",{w:1.25},"Alt",{w:1.25},"Fn",{w:1.25},"Ctrl",{w:1.25},"Esc"]
```

```
        C1  , C2  ,C3 , C4  ,  C5 , C6  ,  C7  , C8  ,  C9 ,  C10 , C11,C12, C13 ,    C14
Row 1 [    ;,    1,  2,    3,    4,    5,     6,    7,    8,     9,   0,  -,    =, backspace]
Row 2 [  tap,    q,  w,    e,    r,    t,     y,    u,    i,     o,   p,  [,    ],    /     ]
Row 3 [ Caps,    a,  s,    d,    f,    g,     h,    j,    k,     l,   ;,  ', Null,   Enter  ]
Row 4 [Shift, Null,  z,    x,    c,    v,     b,    n,    m, comma,   .,  /, Null,  Shift   ]
Row 5 [Ctrl , Win, Alt, Null, Null, Null, Space, Null, Null,  Null, Alt, Fn, Ctrl,  Esc     ]
```

## Features
- Compact 60% layout
- Powered by RPi pico
- Dedicated Fn layer
- Smooth switches
- Stabilizers
- Custom CAD
- Custom PCB

## How It Works
The Keyboard-V2 uses a key matrix to scan all rows and columms. The Fn key enables a secondary layer for additional functionality. The case is 3D printed, with custom PCB and.

<details>
  <summary>Pictures</summary>
<img width="819" height="283" alt="Screenshot 2026-04-09 153726" src="https://github.com/user-attachments/assets/683ec29a-9837-499f-a3dc-e068a6107ffd" />
<img width="1123" height="723" alt="Screenshot 2026-04-10 200309" src="https://github.com/user-attachments/assets/a5c9a06c-92a4-42b2-9aea-1ef65380335c" />
<img width="356" height="474" alt="Screenshot 2026-04-11 184744" src="https://github.com/user-attachments/assets/ef492f3b-a6a6-4367-ad02-a08eb90c64b6" />
<img width="1252" height="813" alt="Screenshot 2026-04-11 184757" src="https://github.com/user-attachments/assets/6d5805df-149f-4ffc-a428-c73a2d6ea812" />
<img width="845" height="754" alt="Screenshot 2026-04-11 211805" src="https://github.com/user-attachments/assets/bea24c99-a701-4e40-b68b-7ce55238d9c0" />
<img width="1226" height="791" alt="Screenshot 2026-04-11 211830" src="https://github.com/user-attachments/assets/634b822b-ab45-448f-886b-0eec131d2406" />
<img width="1307" height="681" alt="Screenshot 2026-04-11 211847" src="https://github.com/user-attachments/assets/2091593e-ace3-4c5b-86ee-856e9e032c6d" />
<img width="1197" height="705" alt="Screenshot 2026-04-11 211753" src="https://github.com/user-attachments/assets/2283c599-4147-489d-87ed-da41f1bbc0f0" />

</details>

<details>
<summary>BOM</summary>

| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
|------|--------|----------|------------------|------|-------------|
| Stabilizers | Stabilizers are used so keys arent wobly and are in place | 1 | 8.00 | https://www.aliexpress.com/item/1005006528731543.html | Aliexpress |
| PCB | On the PCB are all components | 1 | 44.11 | https://jlcpcb.com | JlcPCB |
| Key switch | the actual switch u press to get a signal | 1 | 21.00 | https://www.aliexpress.com/item/1005007459638140.html | Aliexpress |
| Diodes | prevents ghosting | 1 | 3.00 | https://www.aliexpress.com/item/1005007160563285.html | Aliexpress |
| RPi Pico | Brain of the whole keyboard | 1 | 4.30 | https://www.aliexpress.com/item/1005008714908011.html | Aliexpress |
| M2 screws | Small set of M2 screws to hold the keyboard in place | 1 | 7.40 | https://www.aliexpress.com/item/1005006827233117.html | Aliexpress |
| M2xL3xOD3.2, Heatset inserts | Will hold the keyboard together with screws | 1 | 5.00 | https://www.aliexpress.com/item/1005006838108683.html | Aliexpress |
| Keycaps | are on switches | 1 | 15.00 | https://www.aliexpress.com/item/1005007360831985.html | Aliexpress |

</details>

<details>
  <summary>License</summary>

## MIT License

**Copyright (c) 2026 TomasD-git**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

</details>
