## Parallel Barnes-Hut algorithm

The Barnes–Hut simulation (Josh Barnes and Piet Hut) is an approximation algorithm for performing an n-body simulation. It is notable for having order O(nlogn) compared to a direct-sum algorithm which would be O(n^2).

Here I simulate N particles that interact with the physical force of gravity in parallel. The data structures used for the implementation include **Quadtree** and **Sector Matrix**.

Scala has been used to develop the project for the ease of parallel programming. Scala has this plethora of parallel structures available as a part of its general connection framework.

To run:
> prerequisite: sbt - an open source build tool for scala and java  
> clone the repository  
> cd <path to the cloned directory>  
> sbt ... might take some time to initialize  
> compile  
> run ... if it tells you multiple Main classes detected, press 1 and hit enter  