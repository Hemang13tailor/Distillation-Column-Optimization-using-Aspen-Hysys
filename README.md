# Distillation-Column-Optimization-using-Aspen-Hysys

This repository contains the work for optimizing a distillation column using Aspen HYSYS. The project demonstrates the simulation and optimization of a distillation column to separate a tetrahydrofuran (THF) and toluene mixture. 

**Objective:**  
To optimize the reflux ratio and distillate rate of a distillation column operating on a 3700 kg/hr mixture of THF and toluene (44 mass % THF) to maximize profit. The target purities are 99.5 mass % for THF and 94 mass % for toluene.

## Methodology

1. **Component Selection:**  
   Selected THF and toluene with a feed composition of 44 mass % THF.
2. **Simulation Setup:**  
   Set up the distillation column in Aspen HYSYS with 10 stages and a total condenser.
3. **Specification & Optimization:**  
   Added purity specifications for THF (0.995) and toluene (0.94), then set the bounds in the optimizer.
4. **Profit Calculation:**  
   Developed a spreadsheet to calculate profit considering feed cost, product selling prices, and utility costs.
5. **Optimization:**  
   Used Aspen HYSYS optimizer to maximize profit by adjusting reflux ratio and distillate rate.
