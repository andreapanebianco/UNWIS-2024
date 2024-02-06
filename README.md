UnderWater (UW) communications are challenging task due to their environment, which can cause high data corruption and loss. UW  communication channels also experience limited bandwidth, high time variability and much longer delays as compared to traditional terrestrial channels. This leads to frequent retransmissions, which consume valuable energy for the network nodes and shorten their lifetime. One way to cope with these issues is to employ reliable smart protocols that can improve packet routing in a UW network to optimize transmission efficiency, minimize latency, save energy, and ensure network robustness. In this paper we propose BOUNCE, a novel routing algorithm for UnderWater Acoustic (UWA) networks based on Multi-Armed Bandit. BOUNCE considers the channel conditions to route packets to those nodes that can ensure the highest transmission quality, the fastest routing speed, and a balanced energy consumption for the entire network.
The AMUSE agent is implemented in Python and runs as a separate module, external to the DESERT simulator. The Python script encompasses the UCB1 algorithm, and the interfaces required to communicate with the DESERT framework. It considers the total number of packets transmitted and received in the previous decision epoch, and according to both the current epoch and past history, identifies the supposedly best modulation
This choice is finally broadcast through feedback packets to all network nodes for usage in the next decision epoch.
- AMUSE.py is the AMUSE agent
- AMUSE_DESERT_simulation.tcl is the DESERT simulation
- Bash_simulation.sh is the executable with which to repeat n training epochs for AMUSE
- rewards.csv contains the rewards for AMUSE
- actions.csv contains the suggested arms
- synchronization.csv allows the synchronization between DESERT & AMUSE at each time step of the DESERT simulation
- done.csv allows the synchronization between DESERT & AMUSE to finish each epoch
