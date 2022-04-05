# eu-powerplant-validation

Content
-------
This repository contains:
-  data_validation.ipynb, which creates plots and stats
-  download_powerplants.ipynb, which loads the European powerplantfleet with a tool called "powerplantmatching"
-  entsoe_generation_data_request.ipynb, which calls ENTSO-E generation capacity and operation data from the official API


Installation
------------
.../eu-powerplant-validation % conda env create -f envs/environment.yaml

.../eu-powerplant-validation % conda activate vali

TODO
------
- [ ]  Calculate capacity factors per plant (massive point plot/violin/boxpot, y-axis CF, x-axis years)
- [ ]  Investigate any differences in operation comparing the years
- [ ]  Answer. What share is must-run and what share are optional (per country)
