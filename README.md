# sbfspot-Docker

Docker compose file for my SBFspot stack.

You will need to adjust the sbfspot.cfg file to your needs (see: https://github.com/SBFspot ).
On first run you may need to initialize the DB if you use SQLite (see: https://github.com/nakla/sbfspot ).

The volume with the CSV files will get mounted RO in the PVdiary2 stack.


See: https://github.com/Stan-Gobien/PVdiary2-Docker
