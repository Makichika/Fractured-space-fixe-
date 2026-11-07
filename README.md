### Installation CLICK ON CODE AND DOWNLOAD ZIP ON TOP RIGHT OF THIS PAGE, don't forget to unlock the file in properties
### !!!BACK UP YOUR FILE BEFORE JUST IN CASE!!!

Work on W10 11, not tested for linux or W7 you have to tell me if you test it 

Read [instructions for emplacement](instructions%20for%20emplacement.txt) for the file locations and installation steps.

**DO NOT COPY THE WHOLE FOLDER. ONLY COPY AND PASTE THE INDIVIDUAL FILES INTO THEIR SPECIFIED LOCATIONS.**

For Discord avatars, also install the files from `Bootstrapper` into your own Bootstrapper installation folder. The path in the instructions is only an example: **use your actual Bootstrapper folder if its location is different**. Close the game and Bootstrapper before copying.

Server fixes are installed on my servers.

My servers are now always showing in the server list if my PC is on but without using any ressource until someone join.

### Fix micro freezes

For Last Stand micro freezes, press Windows + R.

Open this file:
`%LOCALAPPDATA%\spacegame\Saved\Config\WindowsNoEditor\Engine.ini`

Edit to have 100k or more or add these lines at the end of the file if you don't have them:

```ini
[/Script/Engine.Player]
ConfiguredInternetSpeed=100000
ConfiguredLanSpeed=100000

[/Script/OnlineSubsystemUtils.IpNetDriver]
MaxClientRate=100000
MaxInternetClientRate=100000
```

### Client fixes and Change

| Type | Change |
|---|---|
| **Client** | Fix Destroyer and Interceptor jamming |
| **Client** | Enable the Ready button during pre-draft |
| **Client** | Fix mode names, artwork and list scrolling in the draft menu |
| **Client** | Fix the draft menu not showing other players/bot in pre-draft |
| **Client** | Fix all Venturer skins |
| **Client** | Fix missile red icons and warning sounds |
| **Client + Bootstrapper** | Use the connected Discord profile avatar in the hangar and other players' Discord avatars in scoreboards |
| **Client (optional)** | Group the online server list |
| **Client** | Status effect countdowns follow game time instead of real time on compatible servers |
| **Client** | Keep the Protector shield field visual independent of its personal shield status; fix its asynchronous effect-loading dependency |
| **Client + compatible server** | Restore the Charon event maps, hidden sector, voice hooks and team resource notification (`conquestcharon`) |
| **Client + compatible server** | Restore the Christmas event maps, Omega HUD and Ru-T0lf combat voice hooks (`conquestxmas`) |


### Server fixes and Global change

| Type | Change |
|---|---|
| **Server** | Fix Aegis consuming energy twice when using its particle accelerator |
| **Server** | Fix Last Stand crashes and force players onto the human team (team assignment fix by Tiger) |
| **Server** | Enable the pre-draft lobby and drafting across all my servers |
| **Server** | Fix players getting stuck loading when joining an occupied pre-draft lobby |
| **Server** | Fill teams with bots, adapt filling to 3v3 or 5v5, and give a bonus Venturer to the team with fewer human players |
| **Server** | Enable global pre-draft chat |
| **Server** | No  time duration on Pre-draft; players need to write "ready" to start drafting |
| **Server** | Allow players to vote on enemy bot difficulty in the PvE server; instructions appear in pre-draft chat |
| **Server** | Fixe the paladin purge actually be 5s, to not waste a cooldown, the enemy being purged can't activate self effect only (self boost etc) |
| **Server** | Make missiles, buoys and miners immune to ship destruction damage |
| **Server** | Prevent harpooned or displaced targets from using jump drive for the effect duration |
| **Server** | Let AI target miners when nobody is nearby |
| **Server** | Make AI ignore mines once both teams are at max level and stop shooting miners once its team is at max level |
| **Server** | Keep AI firing at ships during their jump |
| **Server** | Make AI prioritize the central base jump point so it can defend the capture zone |

🧪 Experimental Servers change :

-Centurion's Overload damage from 3k to 4k.
