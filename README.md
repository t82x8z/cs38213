java c
MSE 5610/MEAM 5530 HW 4 
(Part I: Due 11/05; Part II: Due 11/16) 
Equilibrium Molecular Dynamics method 
Part I (Due 11/05/24) 
The starting configuration for both parts will be the block and neighbor map you developed in HW 2. As in previous homework the interaction between the atoms is described by the Lennard-Jones potential for argon that is smoothly cut-off at  rcut = 7.5Å by a polynomial. The constructed block is a cluster with free surfaces. 
(1)       Carry out a MD calculation for this system using the Verlet algorithm with velocities. Start with zero velocities for all atoms so that the kinetic energy is zero at the beginning. As you approach equilibrium the kinetic energy will become finite. Stop the calculation, set the kinetic energy, i.e. velocities, again to zero and continue the MD calculation again. Repeat this until the kinetic energy is small but not zero, corresponding, say to 1 – 2 degrees K. At this point you should get a relaxed structure like that found by molecular statics in HW 3. Check the value of the total pressure and if it is not zero, scale coordinates appropriately and repeat theMD simulation. Display the structure of the block by depicting the atomic positions. Evaluate and plot the radial distribution function (RDF).
(2)       Set T = 5K. Assign to the particles velocities via scaling such that the kinetic energy corresponds to the chosen temperature (the total velocity of the block should remain zero). Continue the calculation until the thermodynamic equilibrium has been attained. (The temperature will be somewhat different than what you assigned and if too different improve the temperature). It is important to equilibrate the MD simulation first and then run for a large number of steps so that the system reaches thermodynamic equilibrium. Display the structure and the RDF as in (1) above.
(3)       Increase the temperature gradually, using scaling of velocities, in steps of about 5K, up to 85 K at least (100K would be ideal). In each case carry out the calculation until the thermodynamic equilibrium has been reached. For submission of Part I, you may do as  many  temperatures  sampling  up  代 写MSE 5610/MEAM 5530 HW 4 Equilibrium Molecular Dynamics methodJava
代做程序编程语言to  85  K  as  possible  (A minimum of  four temperatures are needed for Part I). For Part II submission, your report should include the results for all the temperatures including those in Part I.
Carry out the following analyses for every temperature after reaching the thermodynamic equilibrium:
(a)       Analyze  the  structure of the block by the direct display of atomic positions and by determining the RDF, similarly as in HW 3.  State whether the material is crystalline, liquid or possibly gas at every temperature and briefly explain your answer. 
(b)       Evaluate  the  total  energy  and  total  hydrostatic  pressure  and  plot  their  temperature dependencies.
Part II (Due 11/16/24) 
Question 4 description below is the same as in Part I.
(4)       Increase the temperature gradually, using scaling of velocities, in steps of about 5K, up to about 85 K. In each case carry out the calculation until the thermodynamic equilibrium has been reached. Display and include all plots in intervals of 5K. Carry out the following analyses for every temperature after reaching the thermodynamic equilibrium: 
(a)       Analyze  the  structure of the block by the direct display of atomic positions and by determining the RDF.  State whether the material is crystalline, liquid or possibly gas and briefly explain your answer. 
(b)       Evaluate  the  total  energy  and  total  hydrostatic  pressure  and  plot  their  temperature dependencies.
(5)       Determine the temperature dependence of the relevant specific heat.
(6)       Determine the autocorrelation function of velocities for various temperatures. Display its variation at every temperature as a function of time. 
(7)       Bonus question  1: Calculate for the liquid and/or gas state (not solid state) the self- diffusion coefficient D as a function oftemperature.  Plot ln(D) vs 1/T for T up to 100 K and comment on the meaning of the slope. (5 marks) 
(8)       Bonus question 2: You may simulate a bigger 2D square lattice of your choice for as many temperatures as you can and provide a summary. (5 marks) 







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
