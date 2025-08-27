# README

## **Assets**

The only external assets used are the weapons' meshes and icons.

## **Controls**

**[ WASD ]** <pre>Movement</pre>
**[ Mouse ]** <pre>Camera</pre>
**[ Mouse Right Button ]** <pre>Aim</pre>
**[ Mouse Left Button ]** <pre>Shoot</pre>
**[ R ]** <pre>Reload</pre>
**[ Mouse Wheel Up ] / [ TAB ]** <pre>Select Next Weapon</pre>
**[ Mouse Wheel Down ]** <pre>Select Previous Weapon</pre>

## Content

Everything custom or modified that's used in the project is inside the **00_Main** folder, the other folders are default from Unreal without modifications that are not directly used or relevant.

All the important code is inside the **Blueprints** folder.

## Logic

Everything in the code is versatile and scalable so that adding new weapons, shot effects, interactive areas, etc doesn't require a rewrite or modification, just adding the new elements.

---

To shoot, the Player must be **aiming**.

The **Pistol** is *semi-automatic* and the **Minigun** is *automatic*.

Everything related to weapons is handled through `BPC_WeaponComponent`, while the `BP_Player` handles the input, current status, and its HUD.

---

The Enemy Dummny regenerates Stamina 3s after not taking any damage.

---

The **Interactive Areas** affect any amount of characters that go inside the area for as long as they stay inside.
