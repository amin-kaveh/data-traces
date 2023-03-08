# data-traces
Data traces for Blackhole attack variation in IoT networks over RPL


This repository includes data traces of Blackhole attack variation in IoT networks that use RPL as the routing protocol. All data traces are generated using the Cooja simulator.

The repository includes 23 different attack variations:

1- Basic: one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker continues its attack (advertising the fake rank) until minute 300.

2- On-off (one attacker - 10 min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker continues the attack for 10 minutes and pauses it for 10 minutes. This process continues until minute 300.

3- On-off (one attacker - 15 min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker continues the attack for 15 minutes and pauses it for 15 minutes. This process continues until minute 300.

4- On-off (one attacker - 20 min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker continues the attack for 20 minutes and pauses it for 20 minutes. This process continues until minute 300.

5- On-off (one attacker - 25 min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker continues the attack for 25 minutes and pauses it for 25 minutes. This process continues until minute 300.

6- On-off (one attacker - 30 min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker continues the attack for 30 minutes and pauses it for 30 minutes. This process continues until minute 300.

7- Decreasing (one attacker - rank decreases 1/min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker decreases its advertising rank 1 per minute until it gets to 124. Then it keeps advertising this fake rank value until minute 300.

8- Decreasing (one attacker - rank decreases 2/min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker decreases its advertising rank 2 per minute until it gets to 124. Then it keeps advertising this fake rank value until minute 300.

9- Decreasing (one attacker - rank decreases 4/min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker decreases its advertising rank 4 per minute until it gets to 124. Then it keeps advertising this fake rank value until minute 300.

10- Decreasing (one attacker - rank decreases 8/min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker decreases its advertising rank 8 per minute until it gets to 124. Then it keeps advertising this fake rank value until minute 300.

11- Decreasing (one attacker - rank decreases 16/min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker decreases its advertising rank 16 per minute until it gets to 124. Then it keeps advertising this fake rank value until minute 300.

12- Decreasing (one attacker - rank decreases 32/min): one random node starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The attacker decreases its advertising rank 32 per minute until it gets to 124. Then it keeps advertising this fake rank value until minute 300.

13- On-off (two attacker - 10 min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. This attacker continues the attack for 10 minutes and pauses it for 10 minutes. Then the second attacker performs Blackhole attack for 10 minutes and pauses it for 10 minutes. (attacker1 (10 mins) - pause (10 mins) - attacker2 (10 mins) - pause (10 mins) - ...) This process continues until minute 300.

14- On-off (two attacker - 15 min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. This attacker continues the attack for 15 minutes and pauses it for 15 minutes. Then the second attacker performs Blackhole attack for 15 minutes and pauses it for 15 minutes. (attacker1 (15 mins) - pause (15 mins) - attacker2 (15 mins) - pause (15 mins) - ...) This process continues until minute 300.

15- On-off (two attacker - 20 min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 20 minutes after the RPL DODAG is initiated and stabalized. This attacker continues the attack for 20 minutes and pauses it for 20 minutes. Then the second attacker performs Blackhole attack for 20 minutes and pauses it for 20 minutes. (attacker1 (20 mins) - pause (20 mins) - attacker2 (20 mins) - pause (20 mins) - ...) This process continues until minute 300.

16- On-off (two attacker - 25 min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. This attacker continues the attack for 25 minutes and pauses it for 25 minutes. Then the second attacker performs Blackhole attack for 25 minutes and pauses it for 25 minutes. (attacker1 (25 mins) - pause (25 mins) - attacker2 (25 mins) - pause (25 mins) - ...) This process continues until minute 300.

17- On-off (two attacker - 30 min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. This attacker continues the attack for 30 minutes and pauses it for 30 minutes. Then the second attacker performs Blackhole attack for 30 minutes and pauses it for 30 minutes. (attacker1 (30 mins) - pause (30 mins) - attacker2 (30 mins) - pause (30 mins) - ...) This process continues until minute 300.

18- Decreasing (two attacker - rank decreases 1/min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The first attacker decreases its advertising rank 1 per minute. Then the second attacker does the same. (attacker1 (decreases rank 1/mins) - attacker2 (decreases rank 1/mins) - ...). This process continues in turn until minute 300.

19- Decreasing (two attacker - rank decreases 2/min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The first attacker decreases its advertising rank 2 per minute. Then the second attacker does the same. (attacker1 (decreases rank 2/mins) - attacker2 (decreases rank 2/mins) - ...). This process continues in turn until minute 300.

20- Decreasing (two attacker - rank decreases 4/min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The first attacker decreases its advertising rank 4 per minute. Then the second attacker does the same. (attacker1 (decreases rank 4/mins) - attacker2 (decreases rank 4/mins) - ...). This process continues in turn until minute 300.

21- Decreasing (two attacker - rank decreases 8/min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The first attacker decreases its advertising rank 8 per minute. Then the second attacker does the same. (attacker1 (decreases rank 8/mins) - attacker2 (decreases rank 8/mins) - ...). This process continues in turn until minute 300.

22- Decreasing (two attacker - rank decreases 16/min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The first attacker decreases its advertising rank 16 per minute. Then the second attacker does the same. (attacker1 (decreases rank 16/mins) - attacker2 (decreases rank 16/mins) - ...). This process continues in turn until minute 300.

23- Decreasing (two attacker - rank decreases 32/min): two nodes are chosen randomly as attackers. The first attacker starts Blackhole attack 15 minutes after the RPL DODAG is initiated and stabalized. The first attacker decreases its advertising rank 32 per minute. Then the second attacker does the same. (attacker1 (decreases rank 32/mins) - attacker2 (decreases rank 32/mins) - ...). This process continues in turn until minute 300.
