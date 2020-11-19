ToDo:

CP1.3.2 -> the NoseProbeChute_035 check what param is needed to have by default 0.02 open, but allow more!

Stuff:
- Drag coeff
  - cone +/- 0.5
  - Cone+cyclinder >0.34
  - cyclinder >0.82
  - wing >0.04-0.09
  - https://forum.kerbalspaceprogram.com/index.php?/topic/168595-how-does-drag-work-these-days-anyway/
  - https://forum.kerbalspaceprogram.com/index.php?/topic/182616-the-drag-of-parts/

Other mods:
- research bodies
  https://forum.kerbalspaceprogram.com/index.php?/topic/139473-110x-researchbodies-v1120-17th-oct-jun-2020/

Notes:
- ContractConfigurator
  - LaunchSite: KSC (on: wiki/WaypointGenerator-Behaviour) Does not work?!

Parts & Changes
- RemoteTech
  - Add channel, antenna can only communicate with antenna's on the same channel
  - Add data bandwidth: how much data can go through
  - Alternative, create contract such that it need to have direct communication with a specific vessel and dishes that are specific to the type of contract (e.g. comm dish, TV dish)
- GPS tech
- Break a part / repair parts
- make stuff happen in the background
  - stuff breaking
  - rovers moving based on kOS script
- science is different
  - need to do experiments for a longer time
  - most experiments are more repeatable / first time less % of the total science
  - For most part not bound to biomes -> so not 10-20 location around KSC
  - contracts give more science
- techtree is different Unmanned before manned and tree starts with support for CP1
  - also some parts (e.g. solar and engines) become better of time or get better versions with progressing through the techtree
    - e.g. engine X gets v1, v2, v3 parts that have some ISP and trust improvements
- Contracts:
  - have more contracts or have long-term contracts that run for years
    maybe they show up after a year and check if you have a ship that meets the req with MET > 1 year
    These should give you money -> like a yearly licence to pay for the satelite service

General idea for contracts / stories
- CP 1 - Starting a Space Agency
  learn how to:
  - build and control a rocket
  - go to space (orbit)
  - change and achieve specific orbits
  - make communication satellite network
- CP 2 - Kerbin (SOI) projects
  - ScanSat Kerbin
    - altimeter low
    - biome low
    - resources low
    - visual low
    - altimeter high
    - biome high
    - resources high
    - visual high
    - anomalies
  - weather sat
  - imaging sat -> Now part of scan ScanSat
  - TV network for on the ground -> spawn stuff
  - Communication network for on the ground -> spawn stuff
  - GPS network for on the ground -> spawn stuff
  - bring satelite in (a specific) orbit
  - correct orbit
  - repair a part -> maintanance?
- CP 3 - Manned space fairing
  - bring astronauts to space and back
  - Kerbin space station
    - build contracts
    - doing science on the station
    - bring recourses
- CP 4 - Kerbin & moons exploration
  - Mun & Minmus communication
  - Explore Mun & Minmus
    - unmanned
    - manned
  - setting up satelites:
    - communication
      Delay for controlling rover should be "too" high.
    - scan surface
  - rover missions analyzing surface
  - selecting locations to send manned research missions -> they return!
- CP 5 - Long-term habitation
  - Build a base on the moon(s)
  - selecting location(s) on other planets
  - Build a base on other planets
    - Bring base parts
    - Bring Kerbals
    - Resupply
    - Return Kerbals
- CP A - Aviation
  - Airplane
  - Transport ppl from A to B
  - Create spaceplane :)
  - Communication test links to comm sat contract
- CP B - Mining
  - select mining location on mun/minmus
  - build warf in orbit of Kerbin
  - catch an asteroid.
  - select mining location on other planet
  - build mining base there
  - build more stuff there...
  
- science & tech tree
  - column 6 should be covered by exploration of mun & minmus
    - 13 units @45 science = 585
    - one full set is about 75 science (without Kerbal)
    - landed full set + kerbal = 138 science
    - Need to upgrade science center at 450k cost
    - Mun
      - high orbit 150 science
      - low orbit 225 science
      - one biome landed 552 science (total 17)
    - Minmus
      - high orbit 185 science
      - low orbit 300 science
      - one biome landed 690 science (total 9)
    - without landing: 860 + 140?
      - aviation                45
      - basic rocketry          45
      - stability               45
      - electrics               45
      - landing                 250
      - space exploration       250
      - experimental science    250
      -                         930
    - with landing:
      - com Tech                350
      - adv Elec                350
      - unmanned tech           250
      - Gen construction        250
      - scanning tech           350
      - flight control          350
      - unmanned exploration    150
      - aerodynamics            150
      - fuel systems            350
      - gen rocketry            150
      -                        2700
        
    - simple total with both orbit + 2 biomes: >3000
    - 13*100 = 1300
    - 1700 left over
  - column 7
    - 19 units @ 250 = +/- 5000
    - 3000 by exploration of other planets or more exploration of mun/minmus
    - moho
      - 
      

- satelite for:
  - communication
    - our own ships
    - other planets
    - on the planet
      - satelite phone
      - satelite internet
      - GPS
      - Television
        - Have a television station on planet and have a certain coverage on the planet.
        - Have television satelite(s) -> very high bandwidth and only specific area on the ground, so KSO
  - 

Missions:

Agencies
- Delivery
  - Kamazone
  - K-Express
- AD company
  - Kaymo
  - Kuber
  - Kaibu
  Needs GPS systems
- Countries
  - Koviet Union
  - United States of Kamerika
  - Keuropean Union
  - Kindia
  - Kina
  - Kapan
  - South Kamerika Union
  - Kafrika
  

- Unmanned rockets:
  unmanned probe before manned pod!
  - reach A km height & crash into the ground
  - reach A km height & land safely a remote controlled rocket -> just some mini booster
    - reach A km and a certain location/distance
    - reach A km and two successive locations (needs turning and no wings!)
  - reach B km height & land safely a remote controlled rocket -> just some (mini) booster
  - reach > 70km height & land safely a remote controlled rocket
  - reach space and orbit -> don't land!
  - reach space and orbit -> go back but crash
  - reach space and orbit -> land safely
  - reach space and high(er) orbit -> land safely
  - reach space and high(er) orbit -> high speed >3500m/s when entering atmosphere (check the speed) -> it should burn up!
  - reach space and orbit -> land safely -> Bring heatshield
  - reach space and orbit -> land safely -> Bring something heavy up and down
  + Add bonus if there is also science done

- Satelite missions
  Starting after reaching space with a rocket
  - reach space and deliver a satelite -> orbit for N days, rocket needs to return/destroy
  + Bonusses for when recovering the rocket
  - Recover a satelite
  - Create science satelites -> orbit for N days, and do N measurements?
- ScanSat:
  - Satelite for Kerbin -> certain coverage scanned with types:
    + alti
    + resources
    + biomes
    + HiRes Alti
    + anomalies
- RemoteTech:
  - satelites for Kerbin com
    + extra communication satelites for ON Kerbin (as money making contracts)
  - satelites for com to and from Mun and Minmus
  - KSO satelites for com outside Kerbin SOI
    - non-standard KSO orbids
- GPS satelites
  - bring N satelites in MKO with an non-equatorial orbit

- Manned airplanes:
  Means airplanes before space ?

- Manned rockets:
  - create a pod and do crew report
  - create a pod and launch -> reach A height
 