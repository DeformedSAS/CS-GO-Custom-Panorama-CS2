
# CS2 Panorama UI Backport onto CS:GO.
This small project that i did for unknown reasons brings the CS2 Panorama UI to CS:GO
# NOTE: Always download the updated source code from the home page of the repo instead of the one from releases tab. 

# Whole ui
- All of the core UI changes.
![image](https://github.com/user-attachments/assets/9293bc77-9c86-4671-b851-b92729d6c738)

![image](https://github.com/user-attachments/assets/06f257ff-0b8e-438a-8429-c48b27a7331d)

![image](https://github.com/user-attachments/assets/1297d2e6-7561-4ac0-8214-8b81cf060fe4)

![image](https://github.com/user-attachments/assets/49d95e87-3d8f-4eca-ad22-d1d4ffa34c05)

![image](https://github.com/user-attachments/assets/f5ac7586-f744-4b13-8f76-b1e91d3bfab4)

![image](https://github.com/user-attachments/assets/077edcf3-f314-4ebe-baa1-fc57f5e46477)

![image](https://github.com/user-attachments/assets/c5e6b540-e018-4e38-a9cf-5ed04463cf77)


# Hud changes
![image](https://github.com/user-attachments/assets/410a03c8-ed3c-4183-ad20-355db112ff17)

![image](https://github.com/user-attachments/assets/73a93f41-716a-475e-8c21-58fce38b3754)

# Inventory
- Well it wouldn't really be like CS2 if the inspecting stuff isn't like in CS2. So i added it! PS: Knives cannot be inspected like guns, the reason for that is because valve messed up the center axis of all knife models in the game, for some reason they set the tip of all knives to be the center axis which makes no god damn sense.

https://github.com/user-attachments/assets/19e1afba-f4dc-4300-b37a-bd24c5db00d1

# Credits
- crazymodder and others who worked on porting CS2 weapons to CS:GO. And for giving me permission to use the kukri knife model in this addon!
- d3gk for helping me resolve some issues.
- roblogez for suggestions for hud and improving general code optimisation.
- Valve, CS2 Developer Team for making the awesome clean ui.
- And me DeformedSAS for basically backporting the entire UI..
- ZooL for giving me permission to use his reworked molotov. All he said was do whatever when i asked him so.. I guess it's a yes?

# Installation and Requirements
- You are required to use HLAE!
- MiGi (By the one and only ZooL)
- HLAE panorama loader [panorama.my.zip](https://github.com/user-attachments/files/17939965/panorama.my.zip)

# How to install?
- Download HLAE First. Run HLAE, paste the zip folder above into %appdata%\hlae
- Download MiGi from ZooL's Official MiGi website. https://zoolsmith.github.io/MIGI3/
- Download the addon from releases tab and extract the folder named p_cs2panorama from the zip into migi\csgo\addons and then build! (DO NOT LAUNCH FROM MIGI OR OTHERWISE IT WILL LAUNCH CS2 INSTEAD OF CS:GO!)
- Download the repository code zip and extract the layout, styles and scripts folder to the migi\csgo\panorama folder.
- Also copy the csgo_cs2panorama language file from the LANGUAGE FILE folder from the code zip that you downloaded from the repository code and put it in migi\csgo\resource
- In HLAE go to Tools > Developer > Custom Loader and find your CS:GO install. Then paste these launch options: -language cs2panorama -game migi/csgo -afxdetourpanorama
- If done correctly you should hear the CS2 startup logo and the custom UI should work.
- That's it! Have fun playing with this UI!
