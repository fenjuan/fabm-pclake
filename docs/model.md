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
