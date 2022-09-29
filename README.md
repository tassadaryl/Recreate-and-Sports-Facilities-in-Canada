# Recreation-and-Sports-Facilities-in-Canada
This is the MMA 2023 Python Opt-out Assignment by Lin Ye



## Proposal

After graduation from Rotman, a comfortable place is needed to be chosen for living and working. The first step is to find the best province in Canada. I particularly love natural scenes and love those **trails** and **parks**, so I want to visualize the number of those facilities in each province within Canada, and make comparisons to help me make the decision :) 



## Usage

### Preparation

Python and Conda need to be installed in advance.

Note that some GIS libraries does **NOT** work on newest version of python, let's setup virutal env here.

```bash
cd YOUR_WORKING_DIR
conda create --name ArcGIS python=3.9
conda activate ArcGIS
conda install -c esri arcgis
pip install -r requirements.txt
```



### Run the Code

1. Open main.ipynb in VSCode or Jupyter Notebook, choose the ArcGIS env.
2. Change the `CLIENT_ID` in the second cell to your own one.
3. Run All