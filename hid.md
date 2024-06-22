# HID Handbook

## Replacing HID switches

The circuits to which switches are soldered are likely to be through-holes.
If those hard-to-remove switches are heated for a long time using a desoldering wick, the land will be heated and easily damaged.
Therefore, as far as possible, use the FR-301[^DesolderingToolVideo][^FR-410] and a suitable nozzle to suck out the solder.

Also, when unplugging the internal cable connector, pull on the cable part to pull out the pins, so grab the connector and pull it out.

[^DesolderingToolVideo]: [Instructional videos on how to use the system do not exist on the Japanese language pages.](https://hakkousa.com/products/desoldering/desoldering-tools/fr-301-portable-desoldering-tool.html)
[^FR-410]: [The FR-410 product page is more informative about desoldering.](
https://www.hakko.com/japan/products/hakko_fr410.html)


## Keyboards

```mermaid
flowchart TB
  subgraph 1990s
    subgraph MS-DOS
      direction LR

      pc9801vx(NEC PC-9801VX's Keyboard)-->pc9801bx(NEC PC-9801BX's keyboard)
    end
    
    subgraph Windows 95-NT-98
      direction LR

      pc9801bx-->pc9821cx13("`**NEC PC-9821Cx's keyboard
      CMP-6D0Y7**`")
    end
  end
  
  subgraph 2000s
    subgraph Windows Me-2000
      direction LR

      pc9821cx13-->pcat1(Cheap PC/AT keyboards)
    end
    
    subgraph Windows XP
      direction LR

      pcat1-->nmb
      nmb("`**NMB RT6652TWJP
      CMI-6D4Y6/B**`")-->Logitech(Logitech diNovo Edge)-->nmb
    end
  end
  
  subgraph 2010s
    subgraph Windows Vista-7/Linux
      nmb-->hhkb-lite(HHKB Lite 2)
      hhkb-lite-->filco-m(FILCO Majestouch)
      filco-m-->ae-kb("Apple Extended Keyboard II
      M3501")
      filco-m-->unicomp(UNICOMP UNI0P4A)
      filco-m-->race(KBTalking Race 75%)
      filco-m-->thinkpad1("ThinkPad USB Keyboard
      with TrackPoint
      55Y9003")
      race-->hhkb-pro-jp("`**HHKB
      Professional JP**`")
      hhkb-pro-jp-->kinesis-a("`**Kinesis Advantage
      USB Contoured Keyboard**`")
      kinesis-a-->hhkb-pro-jp
      kinesis-a-- "`Quit using Japanese layouts`" -->ergodox1("`**ErgoDox**`")
      kinesis-a-->thinkpad2("ThinkPad Compact USB Keyboard
      with TrackPoint")
    end

    subgraph macOS/Linux #1
      ergodox1-->teck("`**Truly Ergonomic 209**`")
    end
  end
  

  subgraph 2020s
    subgraph macOS/Linux #2
      teck-->filco-minila-r("FILCO Majestouch
      Minila R Convertible")
      teck-->ergodox2("`**ErgoDox with
      upgraded plates**`")
      teck-->drop-alt(Drop ALT V1)
      drop-alt-->shinobi
      ergodox2-->shinobi(TEX Shinobi)
      shinobi-->ergodox2
      ergodox2-->kinesis-a2(Kinesis Advantage 2)
      ergodox2-->maja("`VULCAN X KBDFANS
      MAJA V2`")
      ergodox2-->hhkb-hybrid("`**HHKB
      Professional Hybrid**`")
    end
  end
```

**HHKB**

- [Alternative controller for HHKB](https://hhkb.io/modding/controllers/)
- [Keycaps](https://www.pfu.ricoh.com/direct/hhkb/hhkb-option/detail_keytop.html)
- [Remapping is apparently possible with HHKB Classic](https://www.reddit.com/r/HHKB/comments/g9ciwp/remapping_the_classic_with_the_hhkbkeymaptool/)


## Pointing devices

### Microsoft Wheel Mouse Optical clones

**SteelSeries RIVAL 3**

![RIVAL 3](https://m.media-amazon.com/images/I/71yIvLJ3PjL._AC_SL200_.jpg)
![RIVAL 3](https://m.media-amazon.com/images/I/711nAJtefqL._AC_SL200_.jpg)

This product has a heavy wheel click, but is otherwise a very good WMO clone. 

- Price: 3000-5000 JPY 

| Type          | Original parts | Replacement parts                                       |
| ------------- | -------------- | ------------------------------------------------------- |
| Middle button | Unknown        | [Panasonic EVQP0E07K](#evqp0e07k)[^EVQP0E07K][^nospace] |

[^nospace]: There is no space here for a 3-pin microswitch.
[^EVQP0E07K]: [Microswitch replacement in Kensington Orbit Scroll](https://www.reddit.com/r/Trackballs/comments/o8ai5q/microswitch_replacement_in_kensington_orbit_scroll/)


**ENDGAME GEAR XM1 RGB Gaming Mouse**

![XM1 RGB](https://m.media-amazon.com/images/I/71ni6FM7pKL._AC_SL200_.jpg)

- Price: 3200 JPY, 59.00 USD
- Wider body than WMO
- Main switch feels very good
- Side buttons easy to press
- Wheel scrolls on it is heavy
- Good cable with soft fabric

| Type            | Original parts                 | Replacement parts |
| --------------- | ------------------------------ | ----------------- |
| Primary Buttons | Kailh GM 4.0 (60±5gf)          |                   |
| Middle button   | Kailh tactile switch (70±10gf) |                   |
| Microcontroller | 32bit STM ARM Cortex-M0 MCU    |                   |


**ROCCAT Burst Core**

![Burst Core](https://m.media-amazon.com/images/I/61GoNz2MS0L._AC_SL200_.jpg)

- Price: 3400 JPY 
- The main switch is optical and is said to prevent chattering
  but the clicking sound is light and cheap but not that unpleasant
- Side buttons are large and easy to press
- Wheel scrolling on it is little heavy
- [Great review](https://www.reddit.com/r/MouseReview/comments/kg4cwk/roccat_burst_core_detailed_review_the_new_budget/?rdt=64162)


### Microsoft IntelliMouse Explorer 3.0 clones

<details>
<summary><strong>SteelSeries RIVAL OPTICAL MOUSE</strong></summary>

![RIVAL OPTICAL MOUSE](https://m.media-amazon.com/images/I/61y50QvUPSL._AC_SL200_.jpg)

The rubber coating on the body of this product undergoes hydrolysis over time.

- Price: 6300 JPY 
- Release date: October 11, 2013

| Type            | Original parts         | Replacement parts |
| --------------- | ---------------------- | ----------------- |
| Primary buttons | Micro switch           |                   |
| Middle button   | TTC Micro switch       |                   |
| Rotary encoder  | Something 11 mm height | Alps EC10E1220503 |
</details>


### Others

<details>
<summary><strong>ELECOM M-CAD01UBBK</strong></summary>

![M-CAD01UBBK](https://m.media-amazon.com/images/I/71xStNk1RFL._AC_SL200_.jpg)

- It has OMRON micro switches
- It does not feel bad to hold
- Some DCC tool operations also require both a middle button click and wheel operation,
  so if you have the time to replace the switch on a regular mouse to create the ideal mouse,
  I recommend you take that route

</details>





### Trackballs

- [USB dongle for remapping using RP2040 different from hasu's](https://www.reddit.com/r/Trackballs/comments/t7paeh/remapping_mouse_buttonsaxes_in_hardware_proof_of/?rdt=60108)
  - [Examples of use](https://yyoshisaur.hatenablog.com/entry/2023/11/08/120000)


**Kensington Orbit Wireless Trackball with Scroll Ring**

![orbit trackball](https://m.media-amazon.com/images/I/61jaG6ZfwGL._AC_SL200_.jpg)

Because of its small size, it could be a better left-hand device for me than the slimblade if the switches is replaced.
The slimblade has a pointer that shifts when the ball is twisted.

- [Disassembly](https://yamori-jp.blogspot.com/2018/11/kensington-orbit-trackball-with-scroll.html)



**ELECOM IST Trackball(M-IT11DRBK)**

![IST](https://m.media-amazon.com/images/I/714XRz6oGSL._AC_SL200_.jpg)

This product uses bearings in the trackball support mechanism. However, all button switches are heavy.
The heavy clicking of the main switches in particular leads to discomfort and fatigue as the time of use increases,
so it is advisable to replace these switches first and foremost.

| Type            | Original parts              | Replacement parts         |
| --------------- | --------------------------- | ------------------------- |
| Primary buttons | Kailh black body/red axis   | [OMRON D2F-01F](#d2f-01f) |
| Middle button   | Kailh black body/black axis | [OMRON D2F-01F](#d2f-01f) |
| Rotary encoder  | Something 11 mm height      | Alps EC10E1220503         |


## Switches

Depending on the construction of the mouse wheel, the microswitch D2F-01F seems to me to have a lighter click feel than the tactile switch EVQP0E07K, even at the same operating force.

### D2F-01F

[Specification](https://components.omron.com/us-en/products/switches/D2F)

| Type            | Description |
| --------------- | ----------- |
| Operating Force | 0.74N(75gf) |

### EVQP0E07K

[Specification](https://na.industrial.panasonic.com/products/switches-encoders-interface-devices/switches/lineup/light-touch-tactile-switches/series/79330/model/79472)

| Type            | Description |
| --------------- | ----------- |
| Operating Force | 0.74N       |


## Pens

**Mitsubishi Pencil Jetstream 0.38 SXE3400381P.T**

![Jetstream](https://m.media-amazon.com/images/I/51MHQGp94pL._AC_SL200_.jpg)

Even in the 2020s, Mitsubishi seems to be better than other stationery manufacturers in terms of writing quality.



## Links

- Softwares
  - Linux
    - [input-remapper](https://github.com/sezanzeb/input-remapper)
    - [piper](https://github.com/libratbag/piper/)
    - [Mouse buttons - ArchWiki](https://wiki.archlinux.org/title/Mouse_buttons)
- Disassembly
  - [A blog about taking apart mice and trackballs](https://michtw.blogspot.com/)
  - [Replacing the support mechanism of the Kensington Pro Fit Ergo Vertical with bearings](https://namachan10777.hatenablog.com/entry/2020/10/18/014710)
    > It should be noted that the static friction coefficient is small
- References
  - PC-98
    - [PC9801 Keyboard - tmk_keyboard wiki](https://github.com/tmk/tmk_keyboard/wiki/PC-9801-Keyboard)
    - [Valuestar in the Valuesky: The PC-9821 V13](https://nicole.express/2021/valuestar-in-the-valuesky.html)
    - [PC-98 Keyboards](http://nkmm.org/yagura/kbd/)
  - Removing yellowing(Ansho ouhen) from ABS plastics
    - [Retrobright - Wikipedia](https://ja.wikipedia.org/wiki/Retr0bright)
    - [Nogujyu Keyboard Mania - How to store the keyboards](http://www2s.biglobe.ne.jp/~qwerty/pc/keyboard.html)
- Reviews
  - 1990-2000s
    - [http://telcontar.net/](http://telcontar.net/)
    - [Atelier silencium](http://www5f.biglobe.ne.jp/~silencium/keyboard/index.html)
    - [Nogujyu Keyboard Mania](http://www2s.biglobe.ne.jp/~qwerty/pc/keyboard.html)
    - [Nogujyu Mouse Mania](http://www2s.biglobe.ne.jp/%7Eqwerty/mouse/)
  - 2000s
    - [Keyboard research(Formerly known as Kenjin)](https://ide-research.net/keyboard/)
    - [Qwerters Clinic](http://ex4.sakura.ne.jp/kb/)
    - [SANDY55](http://sandy55.fc2web.com/)
    - [Neko's trackball room](http://mineko.fc2web.com/box/tb-room/)
    - [Neko's keyboard room](http://mineko.fc2web.com/box/kb-room/)
    - [MouseFan](https://mousefan.telcontar.net/)
  - 2010s
    - [Deskthority Wiki](https://deskthority.net/wiki/)
    - [forPCActionGamer Wiki](https://wikiwiki.jp/fpag/%E3%83%9E%E3%82%A6%E3%82%B9%E3%81%AE%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81)
  - 2020s
    - [Libertouch.net](https://libertouch.net/)
    - [blog](https://note.com/yatsuishi/n/nc3554dc0986e)
