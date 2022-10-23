This folder contains all the instances used in the manuscript: 
"Tool switching problems with tool order constraints" 
by Manuel Iori, Alberto Locatelli, Marco Locatelli, and Juan-José Salazar-González, 
2022.

=====================================================================

The instances were generated according to the Section 6.1 of the manuscript.
The instances are organized in folders and the name of the folders specify the size of the contained instances. More specifically, the names of the folders are of the form "N_M_K" which means that it contains only instances with N jobs, M tools, and K slots.


Content of the input file:

-The second line provides N, the number of jobs.

-The fourth line provides M, the number of tools.

-The sixth line provides K, the number of tools.

-Given a job j in {1,...,N},  line 8+j specifies the subset of tools to be loaded in the magazine before starting the execution of the job j.

-Given a tool u in {1,...,M}, line 10+N+u specifies the setup times required to switch from tool c to all the other tools.

-The last line provides the name of the instance.
