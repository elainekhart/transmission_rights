To run:

1. Download project_tx_risk_derate.py and inputs.zip into the same directory
2. Unzip inputs.zip
3. Add the project information to inputs/project_inputs.csv
4. Create a file in inputs/project_hourly_data that includes the project hourly output and the total hourly availability of LTF transmission rights delivering to the utility
5. Add the PTDFs corresponding to delivery from the project POI to the utility to inputs/PTDFs.csv
6. Update inputs/Utility_LTF_rights.csv with any utility LTF rights that should be considered in estimating the portion of headroom on each path available to the utility. Ensure that the POR/POD combinations corrresponding to these rights are listed in PTDFs.csv
7. Specify the project and Utility_POD in project_tx_risk_derate.py
8. Run project_tx_risk_derate.py
