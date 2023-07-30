# Simulated-Annealing-WhiteSharkOptimizer
%% Simulated Annealing-White Shark Optimizer (SA-WSO)
%The Simulated Annealing-White Shark Optimizer (SA-WSO) is a hybrid optimization algorithm
%that combines the principles of Simulated Annealing (SA) and
%the White Shark Optimizer (WSO). This hybrid approach aims to leverage the strengths of both algorithms to improve the efficiency and effectiveness of the optimization process.
%The SA-WSO algorithm typically follows these main steps:
%Initialization: Generate an initial population of candidate solutions randomly within the search space, as done in WSO [R1].
%Preying Behavior (WSO Phase): Sharks in the population select their prey based on their fitness values, using the hunting behaviour of WSO. This phase promotes exploration and exploitation of the search space.
%Simulated Annealing Phase: Apply the SA algorithm to the best shark obtained from the WSO phase. This phase involves the following steps:
%a. Define the initial temperature and cooling schedule for SA.
%b. Iteratively modify the current solution (shark) by perturbing it and evaluating the neighbouring solutions, similar to the SA algorithm.
%c. Determine whether to accept or reject the neighbouring solution based on the acceptance probability, calculated using the SA acceptance criteria and the temperature.
%d. Decrease the temperature according to the cooling schedule until the termination criterion is met.
%Updating the Population: After completing the SA phase, update the population based on the best solution obtained from both the WSO and SA phases.
%Termination Criteria: The algorithm terminates when a specific stopping criterion is met, such as a maximum number of iterations or achieving a desired level of solution quality.
%The SA-WSO hybrid algorithm combines the global search capability of WSO with the local search and convergence properties of SA. 
%The WSO phase helps explore the search space efficiently, while the SA phase focuses on refining the solutions locally. 
%This combination aims to strike a balance between exploration and exploitation, potentially leading to improved convergence speed and solution quality.
% 
