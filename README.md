# SP1ETH
DIY Adapter PCB and Case for SP1 on the Nintendo Gamecube for a ENC28J60 BBA based on the ETH2GC project by webhdx & Extrems

Must be used with the lastest version of Swiss as of 1788 in order to use the in game BBA features as it supports the hypervisor driver for games.

![20250101_160555-min](https://github.com/user-attachments/assets/ad51ec07-052a-4f06-beb3-a348cb5744a2)


**PCB**

Must be ordered from fab such as jlcpcb with 1.2mm thickness with ENIG surface finish


I used 10CM Female to Male dupont wires to connect the ENC28J60 Mini to the pcb but regular wires can be directly soldered to the pcb and ENC28J60 as well, make sure to follow the pinout below.

I also removed the little black retaining plastic on the ENC28J60 in order to push the dupont connectors closer to the pcb to allow more clearance when closing the case together but you can bend the pins some as I did in the images to help with the 2 case halves closing better.

The case is designed to just snap together without any hardware, printed on an FDM 3D printer in something stronger than PLA, I've used PLA+ as its less brittle.

**Pinout**

| ENC28J60 | Connector PCB |
| --- | --- |
| GND | GND |
| VCC | 3v3 |
| CS | CS |
| SCK | CLK |
| SO | DI |
| SI | DO |
| INT | INT |

![Pinout](https://github.com/user-attachments/assets/888f123f-e1b9-4f99-8cc1-d78d393ff442)

![pcb](https://github.com/user-attachments/assets/eeed6fef-80bc-4758-b355-87f3437c7717)


![20250101_144940-min](https://github.com/user-attachments/assets/bade5464-e983-4122-9b84-47fe855f9afb)

![20250101_145106-min](https://github.com/user-attachments/assets/e177433f-fb8e-4f8d-ab45-0b10693a1797)

![20250101_145139-min](https://github.com/user-attachments/assets/0675542f-4425-421a-b61c-a4837fa8bdd1)

![20250101_145732-min](https://github.com/user-attachments/assets/932a5231-77c0-433b-a60c-6361fea2a9be)

![20250101_151721-min](https://github.com/user-attachments/assets/43bd7c57-95ac-48bf-9e99-cf8c149fbd52)

![20250101_160413-min](https://github.com/user-attachments/assets/2a4909a2-726b-4787-a422-a19dacd460e7)

![20250101_160510-min](https://github.com/user-attachments/assets/32e80608-405a-4285-852a-68d009492315)

![20250101_160601-min](https://github.com/user-attachments/assets/0af12528-8ad6-400a-abbd-f066eff186dd)

![20250101_160623-min](https://github.com/user-attachments/assets/fb4940e0-76b5-4992-b1c5-b1eabc791aad)

![20250101_160939(0)-min](https://github.com/user-attachments/assets/81ff9e7a-e7a7-4c83-845d-8c722685f4c0)

![20250101_164624-min](https://github.com/user-attachments/assets/6144fe8b-a97b-4d00-8265-d2824a8188ae)

