# Boids

The serial python version with a flock size of 50 and window size of 400x400 for 200 iterations.
The 3 intra-flock forces of cohesion, separation, and alignment are at play, as well as inter-flock separtion (fleeing)
![Serial Boids, no hunting](https://github.com/hikir1/Boids/blob/main/400x400-50f-200i-nohunt-serial-animated.gif)

The same version, but with a hunting force and crashing rule added:
![Serial Boids, with hunting](https://github.com/hikir1/Boids/blob/main/400x400-50f-200i-serial-animated.gif)

Running the complete algorithm with the same parameters in our MPI/CUDA implementatino on AiMOS, except increasing the flock size to 1024:
![CUDA boids](https://github.com/hikir1/Boids/blob/main/400x400-50f-200i-serial-animated.gif)
