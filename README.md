##CivpvpInventory [![Build Status](http://vps40435.vps.ovh.ca:8080/job/CivPvP/badge/icon)](http://vps40435.vps.ovh.ca:8080/job/CivPvP/)
---

Inventory saving and loading plugin.

Gives the following commands:

/inv save <name>
/inv load <name>
/inv clear

It will only allow the user that created the inventory to save over it.

In the config you can enable worldguard region checking where only players in the specified regions can use /inv.

TODO:

Use MySQL instead of flat files to hold inventories
Allow players to share write access on inventories
Log who loads which inventory (alt detection?)
