# 3-Bit Binary Adder Circuit

I am making a PCB where you can enter 2 3-bit binary numbers using slide switches, and then it outputs them added via LEDs.

I first designed the logic circuit in Sebastian Lague's Digital Logic Sim, and then converted it to a schematic in Kicad and then a PCB which I used Freerouting to auto-route it. 

<img width="514" height="523" alt="image" src="https://github.com/user-attachments/assets/be5ea14f-ba88-40d9-9218-f99ce5ac3be4" />

# BOM

| Week | Tier | Parts funding |
| --- | --- | --- |
| Week 1 | Tier 1 | $30.00 |

| Part | What it's for | Qty | Unit | Total | Vendor |
| --- | --- | --- | --- | --- | --- |
| [PCB from JLCPCB](https://jlcpcb.com) | The pcb | 1 | $4.00 | $4.00 | [JLCPCB](https://jlcpcb.com) |
| [10x 74hc00](https://www.aliexpress.com/item/1005008583582387.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%201.12!AUD%201.12!!AUD%201.12!!!@2101c4b817917647332913856e0e42!12000045830763407!ct!AU!8282893199!!1!0!) | NAND gates | 1 | $1.12 | $1.12 | [Aliexpress](https://www.aliexpress.com/item/1005008583582387.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%201.12!AUD%201.12!!AUD%201.12!!!@2101c4b817917647332913856e0e42!12000045830763407!ct!AU!8282893199!!1!0!) |
| [LEDs and resistors](https://www.aliexpress.com/item/1005007592187428.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%2013.36!AUD%206.88!!AUD%206.88!!!@2101c4b817917647332913856e0e42!12000041421584236!ct!AU!8282893199!!1!0!) | Glowing | 1 | $6.88 | $6.88 | [Aliexpress](https://www.aliexpress.com/item/1005007592187428.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%2013.36!AUD%206.88!!AUD%206.88!!!@2101c4b817917647332913856e0e42!12000041421584236!ct!AU!8282893199!!1!0!) |
| [10x 14 pin IC sockets](https://www.aliexpress.com/item/1005007539941715.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%206.12!AUD%202.94!!AUD%202.94!!!@2101c4b817917647332913856e0e42!12000041213583452!ct!AU!8282893199!!2!0!) | To solder to PCB without damaging IC | 2 | $2.94 | $5.88 | [Aliexpress](https://www.aliexpress.com/item/1005007539941715.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%206.12!AUD%202.94!!AUD%202.94!!!@2101c4b817917647332913856e0e42!12000041213583452!ct!AU!8282893199!!2!0!) |
| [10x 74hc00](https://www.aliexpress.com/item/1005006186781850.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%208.11!AUD%202.69!!AUD%202.69!!!@2101c4b817917647332913856e0e42!12000036217497113!ct!AU!8282893199!!1!0!) | NAND gates | 1 | $1.49 | $1.49 | [Aliexpress](https://www.aliexpress.com/item/1005006186781850.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%208.11!AUD%202.69!!AUD%202.69!!!@2101c4b817917647332913856e0e42!12000036217497113!ct!AU!8282893199!!1!0!) |
| [20x micro slide switches](https://www.aliexpress.com/item/1005003938407295.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%203.62!AUD%203.62!!AUD%203.62!!!@2101c4b817917647332913856e0e42!12000053184498269!ct!AU!8282893199!!1!0!&pdp_ext_f=%7B%22cart2PdpParams%22:%7B%22pdpBusinessMode%22:%22retail%22%7D%7D) | Representing the binary numbers | 1 | $1.49 | $1.49 | [Aliexpress](https://www.aliexpress.com/item/1005003938407295.html?spm=a2g0o.cart.0.0.202b38daBqYS5y&mp=1&pdp_npi=6@dis!AUD!AUD%203.62!AUD%203.62!!AUD%203.62!!!@2101c4b817917647332913856e0e42!12000053184498269!ct!AU!8282893199!!1!0!&pdp_ext_f=%7B%22cart2PdpParams%22:%7B%22pdpBusinessMode%22:%22retail%22%7D%7D) |
| **Parts subtotal** | — | — | — | **$20.86** | — |
| **Tax & shipping** | — | — | — | **$9.14** | — |
| **Total** | — | — | — | **$30.00** | — |

$0.00 left of the tier's funding.
