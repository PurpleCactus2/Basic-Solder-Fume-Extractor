# Basic-Solder-Fume-Extractor
A simple battery powered fan and filter meant to suck soldering fumes away and filter them out

<img width="4032" height="3024" alt="IMG_0416" src="https://github.com/user-attachments/assets/10382051-ec26-4a17-b5d0-acc5091943e1" />

### Introduction
This is a simple soldering fume extractor meant to pull soldering fumes away from your face and filter them out so that they don't linger in your workspace. It uses a 92mm PC fan as the main extractor along with an AA battery pack for power.

This is my first real electronics project aside from arduino starter kit projects. And because of this, I wanted to make it as simple as possible while still fulfilling some kind of purpose. While I don't actually have a soldering iron yet, I think this will make me prepared for when I actually get one. 

### Assembly and Operation
I have tried to make the physical assembly relatively easy to put together with minimal hardware. The main part uses a "sandwich" of sorts comprised of the fan and filter while the battery holder lies on top. It uses snap fits and glue to put everything together

You'll see what I mean in the exploded view below:

<img width="922" height="615" alt="Exploded View" src="https://github.com/user-attachments/assets/07d4480d-3563-4748-a38c-3eca7b5a6f26" />

Here you can see several key parts of the assembly:
- The main casing (centre) - This houses the fan, filter and all the other structural parts. The battery holder sits above it when assembled.
- The front cover (far left) - This snaps into the front of the casing to prevent the fan from sliding out.
- The fan (left) - This faces outwards, and is inserted with the wires aligning with the groove in the casing
- Spacer (right) - This provides some space between the fan and the filter, allowing the air to spread out across its surface. It can also be used as a stencil to cut out the carbon filter sheets. It slides in behind the
 fan.
- Filter (middle right) - This actually filters out the fumes. It should be cut to size and inserted after the spacer.
- The back cover (far right) - This secures the "sandwich" by snapping into the back on the casing. Note: This part does not sit flush with the back of the casing like the front cover. Instead it goes in further and presses against the filter to secure it. You can see a small groove along the back of the casing where the bump of the snap joint slides along before engaging.
- Battery pack holder (above centre) - This a structural part which simply provides an interface for the battery pack to sit on top of the casing. It also has a cutout where you can route all the wires. It is glued to the top of the casing by applying glue on the 2 rails which touch the sides of the casing as well as on the top surface between the casing and the battery pack holder.
- Battery pack (top) - This is glued to the top of the battery pack holder with the removeable cover pointing up, and the switch and wires facing outwards as well.


As for the wiring, it's very simple, just connect the positive wire from the battery pack to the positive wire of the fan and the same for the ground wires. For the sake of illustration I have provided a basic wiring diagram here:

<img width="1053" height="476" alt="Wiring Diagram" src="https://github.com/user-attachments/assets/12958daf-c3f4-4635-b361-fa216931e9b5" />


After wiring everything up as putting all the parts together, the final product should look something like this:

<img width="4032" height="3024" alt="IMG_0417" src="https://github.com/user-attachments/assets/a192f417-743c-4549-aef0-2793cdf804d8" />

### Media
Here are some videos, photos and screenshots of my design:

CAD screenshot of front:
<img width="902" height="738" alt="CAD" src="https://github.com/user-attachments/assets/d2c2f21e-64bd-4175-b62f-35451381d728" />

CAD screenshot of back:
<img width="897" height="674" alt="CAD (Back)" src="https://github.com/user-attachments/assets/22331aa4-2d2b-42bf-84b8-968d042aa438" />

Some photos of the design:
<img width="3024" height="4032" alt="IMG_0413" src="https://github.com/user-attachments/assets/3041a1f1-ddc0-430d-93f6-b097aa1a1b28" />
<img width="3024" height="4032" alt="IMG_0415" src="https://github.com/user-attachments/assets/00a21215-995e-4c2a-8db4-0842e44bc9d0" />

### BOM
Here is a reference BOM I made in case anyone would want to make this or anything similar:

| Part | What it's for | Qty | Unit | Total | Vendor |
| --- | --- | --- | --- | --- | --- |
| [12V 92mm PC Fan](https://www.aliexpress.com/item/1005003012090486.html?spm=a2g0o.productlist.main.13.59e818612YrFyj&utparam-url=scene%3Asearch%7Cquery_from%3Apc_back_same_best%7Cx_object_id%3A1005003012090486%7C_p_origin_prod%3A&algo_pvid=b7497d91-056f-4397-ae8c-fe02d671c822&algo_exp_id=b7497d91-056f-4397-ae8c-fe02d671c822&pdp_ext_f=%7B%22order%22%3A%221349%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21NOK%2170.54%2126.55%21%21%217.04%212.65%21%402103849717909541352671167e1113%2112000036190187375%21sea%21NO%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ae51daea7%3Bm03_new_user%3A-29895%3BpisId%3A5000000216897880) | For sucking the fumes away | 1 | $5.91 | $5.91 | [AliExpress](https://www.aliexpress.com/item/1005003012090486.html?spm=a2g0o.productlist.main.13.59e818612YrFyj&utparam-url=scene%3Asearch%7Cquery_from%3Apc_back_same_best%7Cx_object_id%3A1005003012090486%7C_p_origin_prod%3A&algo_pvid=b7497d91-056f-4397-ae8c-fe02d671c822&algo_exp_id=b7497d91-056f-4397-ae8c-fe02d671c822&pdp_ext_f=%7B%22order%22%3A%221349%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21NOK%2170.54%2126.55%21%21%217.04%212.65%21%402103849717909541352671167e1113%2112000036190187375%21sea%21NO%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ae51daea7%3Bm03_new_user%3A-29895%3BpisId%3A5000000216897880) |
| [8x AA Battery Holder with switch](https://www.aliexpress.com/item/33041068817.html?spm=a2g0o.productlist.main.48.6c7c2b46omg3bz&algo_pvid=71e42a17-8835-4e68-845e-14ed5b2bd2da&algo_exp_id=71e42a17-8835-4e68-845e-14ed5b2bd2da-45&pdp_ext_f=%7B%22order%22%3A%221706%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21NOK%2131.66%2110.92%21%21%213.16%211.09%21%4021038c6f17909530050816030e1125%2167319495209%21sea%21NO%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ae51daea7%3Bm03_new_user%3A-29895%3BpisId%3A5000000216897880&curPageLogUid=VB6ddZBYjzRB&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A33041068817%7C_p_origin_prod%3A) | For supplying power to the fan while also having an inbuilt switch | 1 | $3.29 | $3.29 | [AliExpress](https://www.aliexpress.com/item/33041068817.html?spm=a2g0o.productlist.main.48.6c7c2b46omg3bz&algo_pvid=71e42a17-8835-4e68-845e-14ed5b2bd2da&algo_exp_id=71e42a17-8835-4e68-845e-14ed5b2bd2da-45&pdp_ext_f=%7B%22order%22%3A%221706%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21NOK%2131.66%2110.92%21%21%213.16%211.09%21%4021038c6f17909530050816030e1125%2167319495209%21sea%21NO%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ae51daea7%3Bm03_new_user%3A-29895%3BpisId%3A5000000216897880&curPageLogUid=VB6ddZBYjzRB&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A33041068817%7C_p_origin_prod%3A) |
| [Carbon Filter](https://www.aliexpress.com/item/1005003090089952.html?spm=a2g0o.productlist.main.1.13716695kepVoe&algo_pvid=87cbb5a2-71bd-431e-a58b-41d3610ea1b0&algo_exp_id=87cbb5a2-71bd-431e-a58b-41d3610ea1b0-0&pdp_ext_f=%7B%22order%22%3A%221190%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21NOK%2153.61%2111.43%21%21%215.35%211.14%21%40210396b417909538826354925e115c%2112000024020486506%21sea%21NO%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ae51daea7%3Bm03_new_user%3A-29895%3BpisId%3A5000000216897880&curPageLogUid=8phGdWWrxuEd&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005003090089952%7C_p_origin_prod%3A) | To filter the fumes | 1 | $5.57 | $5.57 | [AliExpress](https://www.aliexpress.com/item/1005003090089952.html?spm=a2g0o.productlist.main.1.13716695kepVoe&algo_pvid=87cbb5a2-71bd-431e-a58b-41d3610ea1b0&algo_exp_id=87cbb5a2-71bd-431e-a58b-41d3610ea1b0-0&pdp_ext_f=%7B%22order%22%3A%221190%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21NOK%2153.61%2111.43%21%21%215.35%211.14%21%40210396b417909538826354925e115c%2112000024020486506%21sea%21NO%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ae51daea7%3Bm03_new_user%3A-29895%3BpisId%3A5000000216897880&curPageLogUid=8phGdWWrxuEd&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005003090089952%7C_p_origin_prod%3A) |
| **Parts subtotal** | — | — | — | **$14.77** | — |

Some notes:
- For the fan I would recommend getting one with a ball bearing one instead of one with a sleeve bearing even though it is cheaper. Ball bearing ones last a lot longer are are sealed from any soot or dust buildup.
- I think the integrated switch is convenient, but it is not necessary for the design. Integrating an inline switch or potentiometer is also a valid change.





