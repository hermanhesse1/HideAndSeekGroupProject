# HideAndSeekGroupProject
In this project, we explore a 2D adaptation of the popular 'hide and seek' game with inverted rules; only one hider to start with, and multiple seekers. The end goal would be to be the single hider remaining at the end of the episode. 

We design a 2D $10×10$ grid world with one **hider** and four **seekers**, initialised with randomly placed obstacles at a certain 'frequency' percentage of randomness. We set this to be $10%$ and agents only observe their local neighbourhood depending on their role (Manhattan distances of either $2$ or $3$). Seekers can share information about new cells in their vision range or hider sightings, and they receive an intrinsic “curiosity” bonus for exploring unvisited locations. The hider, in turn, is rewarded for each time step it remains uncaught.


