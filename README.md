# Thermal-Housing-Model-Data
Code and data used for a Year 3 group industrial project, on the basis of National grid desiring a thermal housing model that gives electrical demands of typical UK houses using an electric heat pump.

Model was coded in google colab, and I have uploaded the code with both .ipynb and .py but not tested in .py

base_code.ipynb is the base model on it's own, able to run for one day. model.ipynb includes extra functions that allow the model to run for multiple days, and for varying specific input parameters.

ninjatempdata, SolarAngles and SolarI are data csvs from renewables ninja [1], [2], slightly edited to make them easier for the code to read, website: https://www.renewables.ninja/

I have tried to leave enough documentation/comments in the code for it to hopefully be easily understandable - Henry Matthews.




[1] Pfenninger, Stefan and Staffell, Iain (2016). Long-term patterns of European PV output using 30 years of validated hourly reanalysis and satellite data. Energy 114, pp. 1251-1265. doi: 10.1016/j.energy.2016.08.060

[2] Staffell, Iain and Pfenninger, Stefan (2016). Using Bias-Corrected Reanalysis to Simulate Current and Future Wind Power Output. Energy 114, pp. 1224-1239. doi: 10.1016/j.energy.2016.08.068
