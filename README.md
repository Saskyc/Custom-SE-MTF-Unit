# Custom-SE-MTF-Unit
This plugin was created for people that want to use custom teams for their server. This script can be fully customized in the config and everyone can use it as they want. If any bugs DMMe at discord saskyc.

### Config Explanation

* GOTOIF SecondUnit {CHANCE100} <= 33 // Another unit will be used if this unit will not be good for wanting to make more units if you want to use another one copy this config, (If wanted to set chance to 50% just change 33 to 50).

* SAVE {Use_Cassie} True // This is option if you want to change Cassie if not you can set it to any other than True but remember when you want to it **must** be set to True.
  
* SAVE {Clear_Customi} True // If you want to clear custom info after player dies.
  
* SAVE {Players_Role} NtfCaprain // The roles you want to give player. The role types can be found [here](https://exiled-team.github.io/Web/docs/Resources/Intro#roletype-team-side-and-faction).
  
* SAVE {Players_CustomInfo} MTF Alpha-1 // The custom info you want to give player if you do not want to give custom info than leave it blank.

* SAVE {CASSIE_Messeage} The Alpha-1 has landed in the facility lockdown code 5 initiated. // The Custom Cassie messeage you want to send if {Use_Cassie} is Enabled.

* SAVE {9x19_Amount_Ammo} 1 // 9x19 ammo that the team will have. The guns 9x19 ammo is used for: **Com15, Com18, FSP9, Crossovec, Com45**
* SAVE {556x45_Amount_Ammo} 1 // 556x45 ammo that the team will have. The guns 556x45 ammo is used for: **E11SR, FRMG0**
* SAVE {762x39_Amount_Ammo} 1 // 762x39 ammo that the team will have. The guns 762x39 ammo is used for: **AK ,Logicer, A7**
* SAVE {12gauge_Amount_Ammo} 1 // 12 Gauge ammo that the team will have. The guns 12 Gauge ammo is used for: **Shotgun**
* SAVE {44cal_Amount_Ammo} 1 1 // 44 Caliber ammo that the team will have. The guns 44 Caliber ammo is used for: **Revolver**

* SAVE {First_Slot} GunFSP9 // This is the first slow of the inventory if you want to change it you can find the items in [here](https://exiled-team.github.io/Web/docs/Resources/Intro#itemtype)

* SAVE {Eight_Slot} None // This is example if you do not want to give anything on that slot.

* EXECUTESCRIPT CustomTeamSetup // Leave this alone
