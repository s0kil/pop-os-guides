## Review and configure the Logitech MX Keys for linux (Pop!_OS)

![The Logitech MX Keys - US ANSI Layout](../assets/logiMXKeys-us-ansi.png)

## Keys reported by showkey

### Function keys

![Function Keys](../assets/fkeys.png)

#### In F-key mode

From left to right:

| F1 | F2 | F3 | F4 | F5 | F6 | F7 | F8 | F9 | F10 | F11 | F12 | Sound Up |
|----|----|----|----|----|----|----|----|----|----|-----|-----|-----|
| 59 | 60 | 61 | 62 | 63 | 64 | 65 | 66 | 67 | 68 | 87 | 88 | 115 |

#### In Media-key mode

From left to right:

| F1 | F2 | F3 | F4 | F5 | F6 | F7 | F8 | F9 | F10 | F11 | F12 | Sound Up |
|----|----|----|----|----|----|----|----|----|----|-----|-----|-----|
|   |   | 125+15 | 125+30 | 125+32 |  |  | 165 | 164 | 163 | 113 | 114 | 115 |

F1, F2, F6 and F7 are hardware keys only. Their purpose is as follows:

F1, F2: Adjust screen brightness (on laptops/supported monitors) To be tested.

F6, F7: Adjust the keyboards brightness (eight levels).

The **Sound Up** (last key in that row) is not affected by the **Fn** key, and has the same keycode in either mode.

The navigation keys (F3, F4, F5) are labeled as follows:
~~~
F3: Mission Control/Task View
F4: Dashboard Launchapd/Action Centre
F5: Show Desktop
~~~

Rather disappointingly all three keys are hardware coded to (apparently) Windows specific shortcuts.

| Key | Keycode | Shortcut |
|---|---|---|----|
| F3 | 125+15 | Super + Tab |
|---|---|---|----|
| F4 | 125+30 | Super + a |
|---|---|---|----|
| F% | 125+32 | Super + d |


![Device Switch Keys](../assets/dekeys.png)

![NumPad Top Row Keys](../assets/cornerkeys.png)

![Control, Super, Alt](../assets/leftkeys.png)

![Alt, Fn, Control](../assets/rightkeys.png)
