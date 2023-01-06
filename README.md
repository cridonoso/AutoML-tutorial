# Automated Machine Learning Tutorial
## [MIT-Chile workshop 2023](https://sites.google.com/media.mit.edu/mit-chile-hcai-viz/2023-concepcion/student-cohort)


### Download data
All data can be downloaded from [google drive](https://drive.google.com/file/d/1Zzd2VvGQi3jMedu5zCts2cG6ZXEH37Mr/view?usp=sharing).
Once locally,
1. Download the zip file called (`data.zip`)
2. Put the `weather` folder and `water.csv` file into the `./data` folder (you should create if not exists)

### Repository tree
- `AutoML.pdf`: Bibliography   
- `data`: Data folder
  - `weather`: Needed for Ludwig Tutorial
    - `raw/images`: Images of weather scenarios
    - `raw/raw_meta.csv`: Labels and images paths
  - `water.csv`: Accumulated water from [Chilean Ministery of Science](https://github.com/MinCiencia/Datos-CambioClimatico/tree/main/output/agua24_dmc)       
- `Ludwig-Tutorial.ipynb`: Ludwig tutorial  
- `config.yaml`: Config file needed for Ludwig tutorial
- `H2o.ipynb`: H2o Tutorial  
-  `AutoML_SLIDES`: Presentation slides
- `README.md`: Repository README

### Windows warning! :warning:
In order to run H2O on windows, it is necessary to install Java<13 (currently version == 19). 

[Click here to download version 13.0](https://www.filehorse.com/es/descargar-java-development-kit-64/46499/descargar/)
