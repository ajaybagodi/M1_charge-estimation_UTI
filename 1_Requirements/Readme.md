# Introduction
This project deals with a Battery Management system (BMS)are used in many industrial and commercial systems to make the battery operation more efficient and for the estimation to keep the battery state, as long as possible, away from destructive state, to increase battery life time. For this purpose, many monitor techniques are used to monitor the battery state of charge, temperature and current. In the current project, the monitoring system for battery powered electric vehicles (EV) has been implementation tested. This system evaluates and displays the state of charge (SOC) for the considered model battery. The battery information and the obtained results explaining the main characteristics of the system are given by the LCD screen.
# Reqiurements

# High level requirements
|  ID  | Description                                                                                           | Catogary |
|------|--------|---------|
|HLR01|Maintains battery in a state in which it can fulfill its functional design requirements                 |Technical|
|HLR02|Protects the safety of the battery operated devices and detects unsafe operating conditions and responds|Technical|
|HLR03|Protects cells of battery from damage in abuse/failure cases|Technical|
|HLR04|BMS is to keep track the state of charge (SOC) of the battery|Technical|
 
	      
# Low level requirements
|ID |Description|Catogary|
|----|----------|--------|
|LL01|"Coulomb Counting Method" that measures the discharging current of a battery and integrates the discharging current over time in order to estimate SOC|Technical| 
|LL02|Estimation of soc is simple in coulomb counting|Technical|
|LL03|Prolongs life of battery (normal operating cases)|Technical|
	
# Objectives

1.	To understand and calculate the SOC (state of charge) of the battery.
2.	TO develop a mathematical model of the system to obtain the relevant equations.
3.	To solve the model by Simpson’s 1/3rd rule.
4.	To develop C program to obtain the desired result i.e the state of charge of the batter.

# SWOT ANALYSIS

# S-Strength
•	BMS calculates SOC by tracking how much energy goes in and out of the battery pack and by monitoring cell voltages; capacity of battery,resistance, this value can bethought of as a fuel gauge indicating how much battery power is left in the pack.

# W-Weakness
•	Some phenomena, such as decreasing SOC,when the battery is resting, and variations with temperature changes,cannot be captured by the Coulomb counting method also.

# O-Opportunity
•	The coulomb counting method is one of the general and simple methods of estimating the soc. We use it for a baseline comparison for more advanced methods.
•	The coulomb counting method measures the current of the battery and integrates the current over time to estimate SOC.

# T-Threats
•	Complex in AC impedance.
•	Sensitive to the amount and quality of training data.
•	Open loop sensitive to the voltage sensor precision, unsuitable for cell with flat curves.

# 4W’s and 1H

# Who:
Charge estimation of the battery using BMS.

# Why: 
It will increase the life of the battery.

# What:
The purpose of this is to monitors and controls the charging and discharging of rechargeable batteries.

# Where: 
The monitoring system for battery powered electric vehicles (EV).

# How :
The industry will be get benefited by enhancement in estimation accuracy, a recalibration at full and empty states is carried out and an evaluation of the state of health was considered.









 

