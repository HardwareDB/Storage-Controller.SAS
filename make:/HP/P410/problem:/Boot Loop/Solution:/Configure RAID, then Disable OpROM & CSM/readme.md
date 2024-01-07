# Solution:
# Configure RAID, then Disable OpROM & CSM in BIOS!
Steps:
1. enable OpROM & CSM in bios
2. insert HP P410 card & SAS Drives. 
3. Wait for configuration OpROM to "Initialize" then press 'F8' when all //// show!
4. Configure RAID or JBOD arrays.
5. Force Shutdown. This will now boot loop, but you can configure it and the force shutdown/pull the plug.
4. remove HP P410 card & unplug SAS cable
5. Disable OpROM & CSM in BIOS. It will now boot normally, with array configuration applied!
6. Reinsert HP P410 card & plug in SAS cable
7. Install OS.
