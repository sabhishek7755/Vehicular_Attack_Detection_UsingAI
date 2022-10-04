# Vehicular_Attack_Detection_UsingAI
Vehicular attack detedtion using AI

1.Consider CAN bus where multiple ECUs are connected and transmitting data in broadcast mode. Let one ECU among them as victim ECU and 3 tasks have to be co-scheduled on the victim ECU. Considering execution time and periodicity of task Ti in victim ECU are Ci and Pi respectively, the details of the three tasks are <Ti, Pi, Ci>: <T1, 0.2s, 0.01s>, <T2, 0.3s, 0.15s>, <T3, 0.4s, 0.15s>. All the tasks can afford maximum 50% execution skips/drops to ensure their performance. Among T1, T2, and T3, only T1 is transmitted to CAN bus. Therefore, at a time interval of 0.2s, we can see T1 in the CAN bus. Find out all possible co-schedulable execution pattern set of the tasks following EDF.	

2.You do not need to consider scheduling of the tasks on ECUs other than victim ECU.

3.However, you need to generate the CAN traffic. Generate 45 unique message IDs ranging from 1-2047 (decimal). Among them, 35 are periodic and 10 are random. Assign harmonic periods to each periodic message uniformly at random from the 16 divisors of 1000 ms (i.e., 1, 2, 4, 5, 8, 10, 20, 25, 40,50, 100, 125, 200, 250, 500, and 1000 ms). Assign one ID of period 0.2 for task T1.

4.Randomly switch between the co-schedulable patterns across the hyper-period.

5.Now, design an adversarial learning system to learn the most probable instance of the target message T1 that an attacker can target.
