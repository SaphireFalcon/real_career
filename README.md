# real_career

Kerbal Space Program Real Career mod and career pack.

## Playing Real Carreer

This is a mod that replaces the stock contracts.  
The goal is to create contract packs that offer a more real career like experience. The pack combined provide a campaign like experience. However, at the same time allowing for creative freedom in how to play each contract, and launching other rockets that are not part of the contract packs. Though, keep in mind that one needs money, science and reputation to progress in the contract packs. Some contracts give you money, some give you science.

### Looking for contracts

In general always look if there is a contract available. If not, check the left tab () to see what contracts are not yet offered and what requirements are not met. Often this is unlocking a tech, finishing another contract etc.

### Tips

* Create saves after / before each contract
* Use Quick safes when making complex maneuvres
* Create saves of your ships (e.g. name them after the contract)
* ?

## Mods

This mod also depends and supports other mods, here an overview:

### Required Mods

Without these mods it won't work:

- USI Sounding Rockets required for the first carreer stage (to be depreciated)
- ContractConfigurator required to create contracts
- RemoteTech for communication

### Highly Recommended Mods

These mods offer additional stories (contract set):

- ScanSat to scan for resources and more contracts
- kOS to program parts to execute stuff (contracts to come in the future)

### Recommended Mods

- MechJeb to make your life so much easier! Though, some of its functionality can be found in standard KSP, but just a little more difficult.
- TweakScale will allow you to change size parts. The contracts are designed to do without this mod and this mod actually adds a tremendous amount of extra parts just for size. But sometimes you can make more beautiful stuff with the right sized parts.

### To be added Mods

- Station & Base building mods
  - USI MKS
  - StationPartsExpansionRedux
- Life Support mods
  - USI life support
  - ?
- Realism mods
  - Kerbal Construction Time
  - Deadly Reentry

### Unsupported Mods

At the moment none are known. Please report any problems with other mods.

## Starting the game

To start create a new game in career mode with the following settings in the tabs:

- Basic:
  - Turn off "Allow Reverting Flights" (Optional: Extra hard)
  - Turn off "Allow Quick loading" (Optional: Extra hard)
  - Turn off "missing crew respawns" (recommended)
  - Turn off "No entry purchase required on research" (Recommended)
  - Turn off "Enable comm Network" (Not sure if RT overrides this)
  - Starting funds: 0 (recommended, you get enough in the career missions)
  - Starting science: 0 (recommended, you get enough in the career missions)
  - Starting reputation: 0 (recommended, you get enough in the career missions)
  - rewards and penalties: 100% (recommended)
- Advanced:
  - Turn off "Kerbal Level Up Immediately" (There's a part for that)
  - Turn off "Allow Negative Funds/Science" (Else too easy)
  - Turn on "Part pressure limits" (recommended)
  - Turn on "Part G-force limits" (recommended)
  - Turn on "Kerbal G-force limimts" (recommended)
  - Turn on "Resource transfer obeys crossfeed rules" (recommended)
  - Turn on "Part Upgrades" (recommended)
  - Turn on "Require signal for Control" (REQUIRED)
  - Turn on "Plasma blackout" (extra hard)
  - Turn off "Enable extra ground stations" (REQUIRED)
- Contract Configurator:
  - Turn all stock contracts off
  - Turn all other contract groups off.
  
> Turning off reverting flights and allow quick loading makes it harder, but one can always use the normal save and loading options. It's more of a hassle.

### kOS configuration

When using kOS choose RemoteTech communication.

### ScanSat configuration

The default settings are mostly oke. They disable stock scanning and require the more advanced ScanSat settings. Disabling "resource biome lock" will make it a bit more challenging as landing in the right spot is more important.  
It is possible to go completely without this mod, I just never tried that.

## Campaign order

- CP1   fully                 lvl 1-3                       82  / 186k
- CP2   1.1, 3.1-2, 4.1       lvl 4                         145 / ?k
- CP2   5.1                   lvl 5 - Scanning Tech         100 / ?
- CP2   5.1                   lvl 5 - Scanning Tech         55 / ?
- CP2   7.1                   lvl 5 - Experimental Science  290 / ?
- CP3   1.1-3, 2.1-2, 3.1     lvl 5 - Space Exploration     300 / ?
- CP3   3.2                   lvl 5 - General Construction  215 / ?
- CP4   1.1-2                 lvl 5 - Adv El, Com Tech      35  / ?
- CP4   1.3                   lvl 5 -                       335 / ?
- CP4   1.4                   lvl 5 -                       385 / ?
- CP4   2.1-4                 lvl 5 -                       820 / +/- 400k


## Known issues

- Sometimes the contract conditions don't seem to be accepted as completed, eventhough the conditions are met. But after landing (or some other random event) the contract/conditions is completed.
- Timer count down:
  In CP1.8.2 (and others) sometimes the timer of one of the satellites doesn't count down anymore. This seems to be an issue in how KSP visualizes the timer in the contract, it does count down. Change the focus to that satellite and wait for the other timers to finish. Suddenly also the other timer is finished and the contract completed.