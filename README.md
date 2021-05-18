# Bachelor Thesis Oleh Kuznetsov

## Statistical modeling of the COVID-19 related time series

### Folder structure

```
├── README.md
├── readme.txt
├── src
│   ├── data 				                        --- folder with data sets
│   │   ├── changepoints-04-05.csv	                --- data set with detected potential change points.
│   │   ├── nakazeni-vyleceni-umrti-testy-04-05.csv --- data set with information about people infected, cured, dead.
│   │   └── opatreni-04-05.csv			            --- data set with the list of government restrictions.
│   ├── functions			                        --- folder with extra functions (statistical tests and tslot)
│   │   ├── supress.py			                    --- supress Fbprophet warnings
│   │   ├── tsplot.py				                --- time series visualisations
│   │   └── ur_tests.py			                    --- statistical testing
│   ├── notebooks			                        --- folder with notebooks with analysis
│   │   ├── changepoints_analysis.ipynb	            --- change points analysis and visualisation 
│   │   ├── environment.yml			                --- conda environment config
│   │   ├── time_series_analysis_basic.ipynb.       --- notebook with the time series analysis
│   │   └── time_series_modeling_complete.ipynb.    --- notebook with modeling section
│   └── thesis					                    --- source code LATEX 
└── texts                            	            --- folder with BT text
	└── thesis_Oleh_Kuznetsov.pdf                   --- thesis text pdf
```

### Run conda environment action sequence

```python
conda env create -f /src/notebooks/environment.yml
jupter lab 
```
