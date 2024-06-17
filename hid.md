## Replacing HID switches

The circuits to which switches are soldered are likely to be through-holes.
If those hard-to-remove switches are heated for a long time using a desoldering wick, the land will be heated and easily damaged.

Therefore, as far as possible, use the FR-301[^DesolderingToolVideo][^FR-410] and a suitable nozzle to suck out the solder.

[^DesolderingToolVideo]: [Instructional videos on how to use the system do not exist on the Japanese language pages.](https://hakkousa.com/products/desoldering/desoldering-tools/fr-301-portable-desoldering-tool.html)
[^FR-410]: [The FR-410 product page is more informative about desoldering.](
https://www.hakko.com/japan/products/hakko_fr410.html)


## Keyboards

**HHKB**

- [Alternative controller for HHKB](https://hhkb.io/modding/controllers/)
- [Keycaps](https://www.pfu.ricoh.com/direct/hhkb/hhkb-option/detail_keytop.html)
- [Remapping is apparently possible with HHKB Classic](https://www.reddit.com/r/HHKB/comments/g9ciwp/remapping_the_classic_with_the_hhkbkeymaptool/)


## Pointing devices

### Microsoft Wheel Mouse Optical clones

**SteelSeries RIVAL 3**

![RIVAL 3](https://m.media-amazon.com/images/I/711nAJtefqL._AC_SL200_.jpg)

This product has a heavy wheel click, but is otherwise a very good WMO clone. 

- Price: 3000-5000 JPY 

| Type          | Original parts | Replacement parts                                       |
| ------------- | -------------- | ------------------------------------------------------- |
| Middle button | Unknown        | [Panasonic EVQP0E07K](#evqp0e07k)[^EVQP0E07K][^nospace] |

[^nospace]: There is no space here for a 3-pin microswitch.
[^EVQP0E07K]: [Microswitch replacement in Kensington Orbit Scroll](https://www.reddit.com/r/Trackballs/comments/o8ai5q/microswitch_replacement_in_kensington_orbit_scroll/)


**ROCCAT Burst Core**

![Burst Core](https://m.media-amazon.com/images/I/61GoNz2MS0L._AC_SL200_.jpg)

- Price: 3400 JPY 
- The main switch is optical and is said to prevent chattering,
  but the clicking sound is light and cheap but not that unpleasant.
- Side buttons are large and easy to press.
- Wheel scrolling on it is heavy.
- [Great review](https://www.reddit.com/r/MouseReview/comments/kg4cwk/roccat_burst_core_detailed_review_the_new_budget/?rdt=64162)


### Microsoft IntelliMouse Explorer 3.0 clones

**SteelSeries RIVAL OPTICAL MOUSE**

![RIVAL OPTICAL MOUSE](https://m.media-amazon.com/images/I/61y50QvUPSL._AC_SL200_.jpg)

The rubber coating on the body of this product undergoes hydrolysis over time.

- Price: 6300 JPY 
- Release date: October 11, 2013

| Type           | Original parts         | Replacement parts |
| -------------- | ---------------------- | ----------------- |
| Rotary encoder | Something 11 mm height | Alps EC10E1220503 |

### Others

**ELECOM M-CAD01UBBK**

![M-CAD01UBBK](https://m.media-amazon.com/images/I/71xStNk1RFL._AC_SL200_.jpg)
- It has OMRON micro switches.
- It does not feel bad to hold.
- Some DCC tool operations also require both a middle button click and wheel operation,
  so if you have the time to replace the switch on a regular mouse to create the ideal mouse,
  I recommend you take that route.


### Trackballs

- [USB dongle for remapping using RP2040 different from hasu's](https://www.reddit.com/r/Trackballs/comments/t7paeh/remapping_mouse_buttonsaxes_in_hardware_proof_of/?rdt=60108)
  - [Examples of use](https://yyoshisaur.hatenablog.com/entry/2023/11/08/120000)


**Kensington Orbit Wireless Trackball with Scroll Ring**

![orbit trackball](https://m.media-amazon.com/images/I/61jaG6ZfwGL._AC_SL200_.jpg)

Because of its small size, it could be a better left-hand device for me than the slimblade if the switches is replaced.
The slimblade has a pointer that shifts when the ball is twisted.

- [Disassembly](https://yamori-jp.blogspot.com/2018/11/kensington-orbit-trackball-with-scroll.html)



**ELECOM IST (M-IT11DRBK)**

![IST](https://m.media-amazon.com/images/I/714XRz6oGSL._AC_SL200_.jpg)

This product uses bearings in the trackball support mechanism. However, all button switches are heavy.
The heavy clicking of the main switches in particular leads to discomfort and fatigue as the time of use increases,
so it is advisable to replace these switches first and foremost.

| Type           | Original parts              | Replacement parts         |
| -------------- | --------------------------- | ------------------------- |
| Left button    | Kailh black body/red axis   | [OMRON D2F-01F](#d2f-01f) |
| Right button   | Kailh black body/red axis   | [OMRON D2F-01F](#d2f-01f) |
| Middle button  | Kailh black body/black axis | [OMRON D2F-01F](#d2f-01f) |
| Rotary encoder | Something 11 mm height      | Alps EC10E1220503         |


## Switches

Depending on the construction of the mouse wheel, the microswitch D2F-01F seems to me to have a lighter click feel than the tactile switch EVQP0E07K, even at the same operating force.

### D2F-01F

[Specs](https://components.omron.com/us-en/products/switches/D2F)

| Type            | Description |
| --------------- | ----------- |
| Operating Force | 0.74N(75gf) |

### EVQP0E07K

[Specs](https://na.industrial.panasonic.com/products/switches-encoders-interface-devices/switches/lineup/light-touch-tactile-switches/series/79330/model/79472)

| Type            | Description |
| --------------- | ----------- |
| Operating Force | 0.74N       |


## Pens

**Mitsubishi Pencil Jetstream 0.38 SXE3400381P.T**

![Jetstream](https://m.media-amazon.com/images/I/51MHQGp94pL._AC_SL200_.jpg)

Even in the 2020s, Mitsubishi seems to be better than other stationery manufacturers in terms of writing quality.



## Links

- [forPCActionGamer Wiki](https://wikiwiki.jp/fpag/%E3%83%9E%E3%82%A6%E3%82%B9%E3%81%AE%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81)
- [A blog about taking apart mice and trackballs](https://michtw.blogspot.com/)
