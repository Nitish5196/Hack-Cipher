---
title: "Hack Cipher"
github: "https://github.com/Nitish5196/Hack-Cipher"
description: "-"
created_at: "2026-"
total_time: "-"
---
## November 7, 2026: <Cart finalizing >
Hi so first i wanted to make a split keyboard but after choosing the components i found out that it is impossible to make it as a tier 1 project(under $30) so i decided to make my own flipper zero cause i wanted to own it since every "hacker" has it but its not readily available in india due to some laws , so im making my own flipper zero - Hack Cipher . today i finalized all the components and added them as BOM in the half life website![image](https://cdn.hackclub.com/01a1b53a-696d-7bf2-a29a-25055e6a7423/paste-1794041863641.png)![image](https://cdn.hackclub.com/01a1b691-fa48-7d1b-87fc-11ba2ec0be76/paste-1794064380722.png)
 
im tryin to keep my BOM cost optimized so im buying from 3 different vendors so components are under the budget

**Total time spent: 1.3h**

## Nov 7 2026 <PCB schematic>
I began identifying the correct schematic symbols for the modules. I discovered that the number of pins alone is not enough to select a suitable KiCad symbol. The physical arrangement, electrical functions and pin numbering must also be verified. I am documenting each module's pinout and matching it with the appropriate schematic symbol and PCB footprint. ![image](https://cdn.hackclub.com/01a1d329-4a64-7839-a092-10250327a35f/paste-1794544049148.png)

**Total time spent: 0.8h**

## Nov ~~13~~ 15 2026 <PCB schematic-2>

Hey so due to haven i was not able to focus on this but now im gonna lock tf in . for the NFC Readersi  i saw it has 4 pins and 8 pins so i made the schematic for both but after researching about it , i learnt that you can you either one and since i have limited GPIO IO pins on my ESP32 im only gonna use the 4pin one ![image](https://cdn.hackclub.com/01a1df41-646a-7bbf-ac16-36431826a4a4/paste-1794746959012.png) ![image](https://cdn.hackclub.com/01a1df41-b8c9-7fff-958e-8639deb2f338/paste-1794746986299.png)
![image](https://cdn.hackclub.com/01a1df56-bebb-7b0a-95c0-2ec487b49a0a/paste-1794748359780.png)

almost done with the schematic ![image](https://cdn.hackclub.com/01a1df7d-74f2-7963-a5a8-748c11670cda/paste-1794750901313.png)

### Schematic done yay
![image](https://cdn.hackclub.com/01a1df86-ba70-7640-b947-3d7e0e336bd7/paste-1794751507922.png)![image](https://cdn.hackclub.com/01a1df87-4597-7e1e-b158-6dbc1783bc8b/paste-1794751545912.png)
oh wait no ,error in DRC ![image](https://cdn.hackclub.com/01a1df88-339b-70e3-95e5-be9bb8dff9dc/paste-1794751602339.png)

FIXED IT ![image](https://cdn.hackclub.com/01a1df8d-c923-7d13-b9f9-6ac4c5c390a1/paste-1794751971767.png)

### Footprint time!!!
![image](https://cdn.hackclub.com/01a1df8f-6716-7f63-bdda-a27a18ab6c2a/paste-1794752078750.png)
footprint done 
![image](https://cdn.hackclub.com/01a1df96-0eee-7a8d-9d6e-ba09dcc47823/paste-1794752512749.png)

### PCB time 
![image](https://cdn.hackclub.com/01a1dfa2-820d-7873-9c2a-d9fa129e5235/paste-1794753329138.png)
Since this is my first time makin custom edge cuts in kicad it looks a bit t weird (also due to the lack of time ) but it'll work fr or now and since i made it , i love it 
oh when itried to update pcb i got 3 erros with the Q1 but i fixed it now yay 
![image](https://cdn.hackclub.com/01a1dfc2-4f10-7da9-b6cb-86f3600ba187/paste-1794755410190.png)
Almost done with pcb arrangement ![image](https://cdn.hackclub.com/01a1dfcc-52b5-7db4-991b-98a8b68872a7/paste-1794756068715.png)

**Total time spent: 4.7h**

## Nov 15 2026<PCB designing >
![image](https://cdn.hackclub.com/01a1dff7-bb9e-7487-b0c3-26e95f2df05a/paste-1794758913939.png)![image](https://cdn.hackclub.com/01a1dff9-2028-73c7-9be3-2f7d3b84c242/paste-1794759004521.png)
trying to fit all the components in tthe compact pcb is super hard but ill do it !!
![image](https://cdn.hackclub.com/01a1e006-6a82-7d35-83c4-b11b0e877fbd/paste-1794759875680.png)![image](https://cdn.hackclub.com/01a1e007-1cb3-7794-84b3-007677a3bb2f/paste-1794759920406.png)
OKay so i downoaded all the 3d step files from GrabCad and added the 3d step to the components in the PCB and arranged them properly and aligned them to ensure their pins match and are not overlaping . i still need to route all this and make a 3d enclousore for it . 
**Total time spent: **1.2hr**