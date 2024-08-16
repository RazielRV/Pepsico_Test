# Pepsico Test: 
This project aims to analysis supervised machine learning modeling, and dataset detailing customer satisfaction

## Pipeline
The following figure shows the steps that were identified to achieve the goal. Showing in a general way the processes that must be considered to develop each module:

1.- The files have been stored locally in the data folder, these files must be processed, that is, load all the files and extract the fields to store them in an object that can be manageable.

2- Analyzing the extracted data will allow us to show qualitative and quantitative values ​​of the data, as well as determine the quality of the data and be able to choose the most appropriate model for the use case.

3.- Taking into account the state of the data we can choose the model and prepare the environment, process the data, train the model and perform some tests

4.- Visually showing the results will give us a greater understanding of what was achieved

Once we have the portions of each image that contains a graph, they will be sent as input to the models.

![plot](/docs/pipeline_pepsico.png)

## Data

Data can be downloaded from a bucket or drive, the `Encuesta.csv` data will be store it in the `/data` folder:

```bash
unzip 2020.zip -d data/
```

## Enviroment Setup 

### Create enviroment locally

```bash
python3.10 -m venv env
```

```bash
source env/bin/activate
```

```bash
pip install -r app/requirements.txt
```


