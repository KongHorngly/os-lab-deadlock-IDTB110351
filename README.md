LEVEL 1;
![alt text](/Pic/Level1.png)
<<<<<<< HEAD
This Picture is showing deadlock scenario with multiple processes and resource locks in a operating system context.

Level 2;
![alt text](/Pic/level2.png.png)
Just the code of Sync_up and Sync_down.

Level 3;
![alt text](/Pic/level3.png)
This picture is showing the process of locking file by running the the first code (sync_up) and The second Code (sync_down) it's auto create the lock file in mount_alpha and mount_beta directory.

Level4;
![alt text](/Pic/level4.png)
Showing the complete deadlock that try to access to another users and the terminal should be freeze
after sleep for 2second.

Level 5;
 ![alt text](/Pic/level5.png)
Both scripts now request locks in the same order (Alpha → Beta). When executed simultaneously, player_B waits for the player_A run the script instead of forming a circular wait. This prevents deadlock.

Level 6;
![alt text](/Pic/level6.png)
The timeout mechanism prevents indefinite blocking by allowing a process to wait for a limited time. If the lock is not acquired within 5 seconds, the process aborts, preventing system freeze and improving reliability.

level 7;

![alt text](/Pic/level7.png)
The teardown process ensures that all mounted virtual drives are safely unmounted and detached from loop devices. This prevents data corruption and avoids leaving orphaned devices in the system, ensuring stability.
