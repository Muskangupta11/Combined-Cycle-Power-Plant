# Combined-Cycle-Power-Plant
ABOUT THE DATASET : Combined Cycle Power Plant dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.

MY MOTIVE : To apply all regression models on the dataset to find the most accurate prediction of net hourly electrical energy output of the plant.

# How a combined cycle power plant produces electricity? 
This is how a combined-cycle plant works to produce electricity and captures waste heat from the gas turbine to increase efficiency and electrical output.

1) Gas turbine burns fuel:
The gas turbine compresses air and mixes it with fuel that is heated to a very high temperature. The hot air-fuel mixture moves through the gas turbine blades, making them spin. The fast-spinning turbine drives a generator that converts a portion of the spinning energy into electricity.

2) Heat recovery system captures exhaust:
A heat recovery steam generator (HRSG) captures exhaust heat from the gas turbine that would otherwise escape through the exhaust stack. The HRSG creates steam from the gas turbine exhaust heat and delivers it to the steam turbine.

3) Steam turbine delivers additional electricity:
The steam turbine sends its energy to the generator drive shaft, where it is converted into additional electricity.

# BEST MODEL 

When all models are compared the best accuracy i.e of 96.18 is given by random forest regressor with n_estimators=15.
