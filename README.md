# OS-Simulator
This was a group project where we had to make an OS simulator. I was assigned the synchronisarion algorithms. The following algorithms were implemented,
1. Producer Consumer - This problem is faced when two processes use the same resource buffer. This is solved by using a mutex lock. Proper visualisation has been implemented in the simulator.
2. Dining Philosopher - The problem arises when every philospher waits for every other philosopher to drop the fork, hence resulting in a lockdown. This is solved by allowing the philosopher to pick the fork only when boht the forks are available to be picked up.
3. Barrier Semaphore - This is experienced when multiple threads work together to solve a common problem but to proceed, each thread has to reach a pre defined barrier.
4. Reader-Writer - Here the problem of concurrent resource access is experienced. Writing while there are stll readers left is not allowed. 
5. Sleeping Barber - This is a classic inter process communication problem. Please refer the visualisation for the solution

Steps to start the simulator,
1. Clone the repository.
2. Open the "Indes.html" inside the Synchronisation folder.
