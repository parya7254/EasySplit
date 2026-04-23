# EasySplit
A hot-swappable split keyboard with a traditional Layout! It will feature MX Switches, a nice!nano (clone) as the main MCU for both sides, and a battery so that it can be used on the go!

<img width="7022" height="3871" alt="image" src="https://github.com/user-attachments/assets/cd9c64a7-4b01-4ca0-9278-0500d2b47ace" />

# Why Did I Make This??
In school, I type A LOT. And typing on a school chromebook, is well, okay I guess, and I want to have a better typing experience when I type things, and well, I like making my own things and finding my own solutions. So I made this split keyboard. It's wireless, battery-powered, and best of all, **made by ME**. This keyboard will help me type my essays faster, work more efficiently, and also turn in my assignments **ON TIME**. *Ahhh*, yes, that's the feeling of making your own solutions and being proud of it.

# How Was it Made??

The PCB was designed using KiCAD and the case for it was designed in Fusion360. The pictures of the schematic and the PCB are below: 

This is the schematic which was designed in KiCad:

<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/38285061-4bbb-4ab2-9dcb-54adde9e525e" />

<img width="3507" height="2480" alt="image" src="https://github.com/user-attachments/assets/69f23db0-47b6-4d60-bd07-614da082848f" />


And this is the actual PCB which was also designed in KiCad:

<img width="741" height="326" alt="image" src="https://github.com/user-attachments/assets/d02c9b6d-c9d5-4898-ad70-ddce199698c5" />


# BOM
These will be the parts that I will use to build and assemble my split keyboard along with the links to get them:

| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
|---|---|---|---|---|---|
| PCB Mount Stabilizers Set | These will prevent wobble when pressing longer keys from the sides! | 1 | 9.99 | https://www.amazon.com/GLORIOUS-Stabilizer-Mechanical-Keyboards-Compatible/dp/B09MZKFLXP/ref=sr_1_11?crid=3RFHAMHTNJHMG&dib=eyJ2IjoiMSJ9.9YfniIYaI-o34quoUu90m7zDr_4-foZ02jjPyDsEARzManorqQYa6ZkiAFErbBYz9TJuFXxpvDujok1W_1GRjgDa590DVzDtTGkG6Xh_kpqE4J4WVSiltDxGBJGeT53EcB3SBohweSioHIYonhLunzFAnVlRzmlw392s7P5Y-ygEsz6do-rmtYWQWlLm-_e1SrFS_aQOEGLgY0bUju37htZfIy6dxoZGQ2pbllG9UMk.Yb2CN95_rwPP4mfPHbmCvu_JmEHeBNfJUVtKBVDAguc&dib_tag=se&keywords=pcb+mount+stabilizers&qid=1776718122&sprefix=pcb+mount+stab%2Caps%2C190&sr=8-11 | Amazon |
| MX Hotswap Sockets (110pcs) | These will be the hotswap sockets for my split keyboard! They will allow for the switches to be removable and replaceable. | 1 | 7.99 | https://www.aliexpress.us/item/3256807045726008.html?spm=a2g0o.productlist.0.0.657f320fXHTJl2&mp=1&pdp_npi=6%40dis%21USD%21USD+15.68%21USD+7.99%21%21USD+7.91%21%21%21%402103212317767176015606506e49b7%2112000039893759777%21ct%21US%21861143113%21%211%210%21&gatewayAdapt=glo2usa | AliExpress |
| 2.0mm JST Connector 2 Pin (5 Pairs) | This will be used to connect the battery to the nice!nano and using this, the battery can also be quickly removed without needing to be desoldered in case of problems or to power off the keyboard. | 1 | 1.76 | https://www.aliexpress.us/item/3256802377876396.html?spm=a2g0o.productlist.main.2.528bk41Bk41BIr&algo_pvid=a5cc2e91-e8b2-44ad-ad58-03e8853783e8&algo_exp_id=a5cc2e91-e8b2-44ad-ad58-03e8853783e8-1&pdp_ext_f=%7B%22order%22%3A%223327%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.81%211.76%21%21%211.81%211.76%21%402101e07217766497385135832ef455%2112000021168869428%21sea%21US%21861143113%21X%211%210%21n_tag%3A-29919%3Bd%3A19af3db4%3Bm03_new_user%3A-29895&curPageLogUid=LA39YhNAYM0j&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005002564191148%7C_p_origin_prod%3A | AliExpress |
| nice!nano Clone | This will be the main MCU for both sides of my keyboard! It will basically read the key presses and send the respective key commands to the connected device. And it also has Bluetooth and a charging IC which means that the two halves of my split keyboard would be wirelessly connected and I can also directly charge my battery from it. | 2 | 5.52 | https://www.aliexpress.us/item/3256807196955871.html?spm=a2g0o.productlist.main.2.3ce24221tMfSLb&algo_pvid=779ced16-8c06-4ba7-8c56-df3f4f68349a&algo_exp_id=779ced16-8c06-4ba7-8c56-df3f4f68349a-1&pdp_ext_f=%7B%22order%22%3A%221388%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%212.76%212.76%21%21%212.76%212.76%21%402101e2b617766476966281993eb7ff%2112000047100969961%21sea%21US%21861143113%21X%211%210%21n_tag%3A-29919%3Bd%3A19af3db4%3Bm03_new_user%3A-29895&curPageLogUid=SquxnhThzcZj&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007383270623%7C_p_origin_prod%3A | AliExpress |
| 1N4148W SMD Small Signal Fast Switching Diodes (100pcs) | These will be the diodes that will be used in my switch matrix that will also help the microcontroller to read the pressed switches properly! | 1 | 1.38 | https://www.aliexpress.us/item/3256805388348871.html?spm=a2g0o.productlist.main.5.3b99CEnvCEnvvu&algo_pvid=07492d90-a3b7-4c77-a77a-7ac091250105&algo_exp_id=07492d90-a3b7-4c77-a77a-7ac091250105-4&pdp_ext_f=%7B%22order%22%3A%22188%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.38%211.38%21%21%219.40%219.40%21%402103212317766487710596971e49be%2112000033607802195%21sea%21US%21861143113%21X%211%210%21n_tag%3A-29919%3Bd%3A19af3db4%3Bm03_new_user%3A-29895&curPageLogUid=HwWnlNgIq0oD&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005574663623%7C_p_origin_prod%3A | AliExpress |
| ELUTENG Ice Blue Mechanical Keyboard Switches (100pcs) | These will be the switches that will be used in my keyboard! | 1 | 15.99 | https://www.amazon.com/gp/product/B0DHCLLH33/ref=ewc_pr_img_1?smid=A3GES9IA7UE877&th=1 | Amazon |
| 3.7V Battery (2pcs) | This will be the battery that will power both halves of my keyboard! | 1 | 8.35 | https://www.aliexpress.us/item/3256811793052939.html?spm=a2g0o.productlist.main.2.23c36977YjUcwi&algo_pvid=7580c894-dc23-495c-9eec-c1519ccc4fcb&algo_exp_id=7580c894-dc23-495c-9eec-c1519ccc4fcb-1&pdp_ext_f=%7B%22order%22%3A%2214%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%2110.10%216.77%21%21%2168.60%2145.96%21%4021033d9d17766495366072792e2a75%2112000057189289229%21sea%21US%21861143113%21X%211%210%21n_tag%3A-29919%3Bd%3A19af3db4%3Bm03_new_user%3A-29895&curPageLogUid=TjlHmkcBk2xm&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005011979367691%7C_p_origin_prod%3A | AliExpress |
| Keycap Set | These will be the keycaps that I will use for my keyboard! | 1 | 14.39 | https://www.amazon.com/gp/product/B0BK3HK7SR/ref=ox_sc_act_image_1?smid=A157804XWFVRE0&th=1 | Amazon |
| PCB (Left and Right) MOQ: 5 | This will be my split keyboard's circuit board! | 5 | 34.00 | https://jlcpcb.com/ | JLCPCB |

