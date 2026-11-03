### Installation

Read [instructions for emplacement](instructions%20for%20emplacement.txt) for the file locations and installation steps.

**DO NOT COPY THE WHOLE FOLDER. ONLY COPY AND PASTE THE INDIVIDUAL FILES INTO THEIR SPECIFIED LOCATIONS.**

All changes made so far. Client fixes are available on this GitHub; server fixes are installed on my servers.

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

### Client fixes

at the end of the file

### Client fixes

| Type | Change |
|---|---|
| **Client** | Fix Destroyer and Interceptor jamming |
| **Client** | Enable the Ready button during pre-draft |
| **Client** | Fix mode names, artwork and list scrolling in the draft menu |
| **Client** | Fix the draft menu not showing other players/bot in pre-draft |
| **Client** | Fix all Venturer skins |
| **Client** | Fix missile red icons and warning sounds |
| **Client (optional)** | Group the online server list |
| **Client** | Status effect countdowns follow game time instead of real time on compatible servers |
| **Client** | Keep the Protector shield field visual independent of its personal shield status; fix its asynchronous effect-loading dependency |
| **Client + compatible server** | Restore the Charon event maps, hidden sector, voice hooks and team resource notification (`conquestcharon`) |
| **Client + compatible server** | Restore the Christmas event maps, Omega HUD and Ru-T0lf combat voice hooks (`conquestxmas`) |

The event PAKs require a server configured for the corresponding event and the updated draft menu scripts. They do not enable events on every Conquest server. See the installation instructions for requirements and verification limits.

### Server fixes

| Type | Change |
|---|---|
| **Server** | Fix Aegis consuming energy twice when using its primary ability |
| **Server** | Fix Last Stand crashes and force players onto the human team (team assignment fix by Tiger) |
| **Server** | Enable the pre-draft lobby and drafting across all my servers |
| **Server** | Fix players getting stuck loading when joining an occupied pre-draft lobby |
| **Server** | Fill teams with bots, adapt filling to 3v3 or 5v5, and give a bonus Venturer to the team with fewer human players |
| **Server** | Enable global pre-draft chat |
| **Server** | Force late arrivals to spectate on the locked Conquest server only |
| **Server** | No  time duration on Pre-draft; players need to write "ready" to start drafting |
| **Server** | Allow players to vote on enemy bot difficulty in the PvE server; instructions appear in pre-draft chat |
| **Server** | Fixe the paladin purge actually be 5s, to not waste a cooldown, the enemy being purged can't activate self effect only (self boost etc) |

🧪 Experimental Servers change 

-Centurion's Overload damage from 3k to 4k.

-Missile, buoy, miner are now immune to ship destruction damage.

-Target being harpooned or displaced now can't use jump drive for the duration.

-AI can now target miner if nobody is around.

-AI now ignore Mine once both team are at max lvl and stop shooting miner once the team is at max lvl.

-AI now keep shooting you when you jump, no more cheesing them.

-AI now prioritize the jump point in the middle of the base instead of the one far away so they can actually defend the capture zone.
