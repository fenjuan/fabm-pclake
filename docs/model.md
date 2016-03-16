# Observations
**Observation files here refer to in-lake measurements, used for calibration**
## Observation files location
../Obs/..
## Temperature
### Checking on Mar.1st
Surface Temperature, OK <br/>
Bottom Temperature:from 2007, the data need to modified manually according to temp_profile_obs.dat <br/>
## Other observed variables
Bottm:/Obs/Fure_bottom_26m_chem.csv <br/>
OBS: Modified March 1st. <br/>
Surface:/Obs/Fure_surface_biochem.csv  



##Model set up directory:
**1D:** /GOTM/ <br/>
**3D:**/GETM/
## Model set ups:
**lake_fure.xml**
## Meteo data
**meteo_file.dat**
## Inflow and outflow
**flow data:** inflow.dat, outflow.dat <br/>
**chemistry data:** inflow_chem.dat <br/>
*inflow and outflow chemistry data is merged to one(orignially there is 3 inflows). The results match ODA calculation*
## Working flow:
**export GOTMDIR=~/GOTM/Lake**<br/>
**make namelist** <br/>
** Compare_results.sh** <br/>
**view results(pdf files) in ../Model_performance/.**


## **Calibration:**
###**Step 1:** Temperature: OK <br/>
###**Step2:** Oxygen: oxygen profile is forced in, so OK <br/>
###**Step3:** Calibrate the bottom variables <br/>
--Phosphate:
