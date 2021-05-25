# X4 MOD: Assign to station
X4 mod: assign ship(s) to station and keep their custom behavior

You can assign ship to station and keep their custom behavior role, station manager will not override it. 

**Use cases:**
1. Miners - miners try to gather resources in different sectors, when I already have rich enough sector with all requires resources, to fix this - I create mining fleet with sector mine job and set individual rule to sell only to my own station in this sector
This problem it's a management of such fleets, for example to mine in one sector 5 different resources I need to create 5 different fleets and in later games the number of fleets expand and it's require a lot of activity to monitor them, instead of just open concrete station in sector and see all ships assigned to this station

1. Patrol fleets - I have a lot of patrol fleets in different sectors, which can use different jobs, from different mods like: reaction force, sector patrol or maybe custom attack in range + repeat variant. It's again in later game force me to create a lot of fleets.

1. Traders - I use MOD Extended Mule and Warehouses and it already somehow do this, when you assign any mule to station it keep selected behavior, so on this part it's already implemented, but anyway why don't assign ship with vanilla custom trade rule to specific station.

# How to use:
Just select ship or fleet and right click on station and select "Assign to", that's all this ship (fleet) will be under new group with defence role but custom behavior will be keeped

# Known issues
Miners and Traders not work as expected (their ignore initial behavior because probably station manager assign new task themself), only military ships or ships with another than trade/mine order (like inventory collector for example) keep they custom behavior

# Installtion
1) Just download latest release as ZIP archive (click on Releases and select latest release archive)
2) Unpack it into the [Path to X4]/extensions/ 

So as result will be created new one folder with mod content: [Path to X4]/extensions/X4_assign_to_station-0.0.2

