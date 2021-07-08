# Dockerized Jupyter-Lab for time series analysis

## Creating a realistic time series forecasting tool.

                                                                            Oussama Tahiri Alaoui, 05-07-2021
                                                                            
This README documents the steps to get JupyterLab up and running.

## Contents

This project is a containerized environment containing a JupyterLab that can be launched and run locally.  
The needed dependencies are addressed in `requirements.txt` (inside the folder `docker`).

## Requirements

Make sure you have installed `docker` and `docker-compose` in your machine. Click [here](https://docs.docker.com/compose/install/) for further info.

## How to run it

Just type in the command line:

```cmd
docker-compose -f <PATH>/docker-compose.yml up --build
```

or in the docker-compose.yml file directory:

```cmd
docker-compose up --build
```

This will create the container and launch Jupyter-Lab.
The port mapping is  `8888:8888`.
The access token is provided once the `docker-compose` command is executed in the command line.
Click on the access token link in the command line (example `http://127.0.0.1:8888/?token=...`), or copy it to the browser to open the Jupyter-Lab.

Once Jupyter-Lab is open on your browser you can open `Time_series_analysis.ipynb` notebook that contains the different analysis steps documentation.

## Contact

Please, do not hesitate to contact me if you have any doubt:

- email: tahiri.oussup@gmail.com
- linkedin: <https://www.linkedin.com/in/oussamatahiri/>