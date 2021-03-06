# basic_dFBA

**basic_dFBA** is a python tool for those with little to no programming knowledge but are interest in biological models. With the support of Excel and a constraint-based model, it can perform a dFBA with a Static Optimization Approach (SOA).


## Installation

Download the scripts *excel_maker_&_xml_reader.py* and *bounds_redefin_&_dfba.py* and include them in the same directory as your constraint-based model. Make sure that in this directory there is only one xml file (constraint-based model).
Recomend use Anaconda.

### Package Requirements:

  - cobrapy
  - openpyxl
  - sympy
  - numpy
  - scipy
  - matplotlib


## Usage

In Spyder (anaconda3), if you opted to use Anaconda, run your script named "excel_maker_&_xml_reader.py". 

This script will create an excel file named *dfba.xlsx* for you to complete (see example dfba.xlsx).

After completing the excel file run script *bounds_redefin_&_dfba.py* to perform the dfba and wait till a file named *plot.pdf* appear in your directory.

Open dfba.xlsx to see all the reaction flow changes in the fluxes tab.

### Warnings

  - Please do not use symbols or numbers in your variable names (state and dynamic_constraints tab)
  - Before running script *bounds_redefin_&_dfba.py* do not modify fluxes tab
  - Do not modify or delete any excel cell, line, collumn or tab with text

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.