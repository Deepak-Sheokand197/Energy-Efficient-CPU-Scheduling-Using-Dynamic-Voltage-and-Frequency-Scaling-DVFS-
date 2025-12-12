Energy-Efficient CPU Scheduling Using Dynamic Voltage and Frequency Scaling (DVFS)
This module provides two different operating strategies:
•	Maximum Performance Strategy: All processes run at the processor's fastest speed (100%) without considering their importance level. This approach prioritizes speed over power consumption.
•	Green Energy Strategy: Processes run at different speeds depending on their importance classification. This approach balances speed and power usage through intelligent frequency adjustment.
Users can easily switch between these strategies to compare the power consumption differences.
	Speed Assignment Based on Importance:
	Important Tasks: Run at 100% processor speed (maximum)
	Regular Tasks: Run at 80% processor speed in energy-saving mode
	Background Tasks: Run at 60% processor speed in energy-saving mode
	Power Calculation: Uses the cubic relationship where power consumption equals speed cubed (P=F^3)[3]
	Execution Duration: Calculated by dividing workload by processor speed (T=Workload/Speed)
	Total Energy Used: Determined by multiplying power by duration (E=P×T)


