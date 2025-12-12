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
	This module displays real-time results and performance information:
•	Bar Chart Display: Bar height shows power consumption level, while bar width shows execution duration
•	Color Scheme: Red indicates high-priority tasks, orange indicates normal tasks, and green indicates low-priority background tasks
•	Information on Hover: When users point to bars, the system displays frequency percentage, power consumption in watts, execution time, and energy used
•	Performance Metrics:
o	Combined completion time across all tasks
o	Combined energy consumption across all tasks
o	Efficiency improvement percentage compared to maximum performance mode



