# Example of application of _dm4bem_: toy model house

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cghiaus/dm4bem_toy_model/HEAD)

Short presentation of modeling described in section _Pyhton script_ of [Inputs and simulation](https://cghiaus.github.io/dm4bem_book/tutorials/pd05simulation.html) chapter of Jupyter book on [Dynamic Models for Building Energy Management](https://cghiaus.github.io/dm4bem_book/intro.html).

Detailed information:
- [toy model house](https://cghiaus.github.io/dm4bem_book/tutorials/02_2_0Toy.html);
- [assembling thermal circuits](https://cghiaus.github.io/dm4bem_book/tutorials/pdREADME.html).

## Folders and files
- __bldg__: description of the building ([link](https://cghiaus.github.io/dm4bem_book/tutorials/pd02bldg2TCd.html?highlight=tc0%20csv))
    - _assembly_list.csv_: list of nodes that merge ([link](https://cghiaus.github.io/dm4bem_book/tutorials/pd03assembleTCd.html));
    - _TC0.csv, ... , TC3.csv_: thermal circuits;
    - _wall_types.csv_: composition of walls ([link](https://cghiaus.github.io/dm4bem_book/tutorials/pd01wall2TC.html));
    - _wall_out.csv_: data for specific wall of _wall_type_.
- __weather_data__:
    - _FRA_Lyon.074810_IWEC.epw_: EnergyPlus weather file ([link](https://cghiaus.github.io/dm4bem_book/tutorials/01WeatherData.html)).
- _dm4bem.py_: Python module;
- _pd05simulation.py_: example of application ([link](https://cghiaus.github.io/dm4bem_book/tutorials/pd05simulation.html)).
- *run_pd05simulation.ipynb*: Jupyter notebook to run the script _pd05simulation.py_.