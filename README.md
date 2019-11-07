# DL-MSS

Deep Learning followed by Moment Scaling Spectrum

**Jupyter notebooks:**
* [Multiple State Generator](./notebooks/MA_MultipleStateGenerator.ipynb)
* [Data processing script](./notebooks/MA_DataProcessing_UserFriendly_NEW.ipynb)

**Jupyter notebooks in HTML format for browsin in the browser, showing the code and the results:**
* [Multiple State Generator](./notebooks_html/MA_MultipleStateGenerator.html)
* [Data processing script](./notebooks_html/MA_DataProcessing_UserFriendly_NEW.html)

**Data files:**
* [Trained model](./notebooks/Model_Bidirectional_NoShape_3state_Tr10000)
* [Model Parameters???](./notebooks/Parameters_Model_Bidirectional_NoShape_3state_Tr10000.txt)

**Required python packages:**
* numpy
* scipy
* matplotlib
* seaborn
* ipywidgets

**Installation of 'ipywidgets' and enabling of 'Initialization cells':**

```python
pip install ipywidgets
jupyter nbextension enable --py widgetsnbextension

pip install jupyter_nbextensions_configurator jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
jupyter nbextensions_configurator enable --user
```



In the Jupiter notebook, in the last tab “Nbextensions” the following extensions should be activated:
'Initialization cells':

![Activating Initialization Cells](./initcells.png)
