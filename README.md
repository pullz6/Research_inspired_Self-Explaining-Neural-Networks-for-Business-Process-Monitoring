# Research_inspired_Self-Explaining-Neural-Networks-for-Business-Process-Monitoring

This project is insipred by https://arxiv.org/pdf/2503.18067v1. We attempt to re-create and deploy this model as a RESTful API. 

## Table of Contents

1. [Project Overview]
2. [Installation]
3. [Project Structure]
4. [Planned Changes]
    
## Project Overview

### About

The intention of the project in a more business sense is explained in the research paper as  "explaining why an algorithm predicts a lengthy wait for a hospital procedure or foresees a bank customer declining a loan offer is vital for offering valuable insights to stakeholders and clients." 

It is also to be noted that follows a methodology akin to the general self-explaining framework (Alvarez Melis and Jaakkola, 2018) and its more recent adaptation to the sufficient explanation setting (Bassan et al., 2025)

Code for the original model - https://github.com/verenich/ProcessSequencePrediction/tree/master 

Architecture of the LSTM model

Below is the diagram of the model.

![image](https://github.com/user-attachments/assets/2b6b4b01-3aad-4e3d-96ae-b5cfbdefe175)


## Installation

### Prerequisites

1. Python
2. ngrok (so we can use the Mlflow though google colab)
3. Mlflow
4. Keras
5. Fastapi (to create the API) 
6. Docker (to containerize the image) 

## Project Structure

```bash
bash
Copy code
project-root/
│             
├── data/                # The Data for training and testing
├── model/               # The Google colab for
├── Dockerfile/          # The dockerfile for the fastapi deployment
├── main.py/             # Fast api deployment
├── README.md            # Project documentation
└── requirements.txt     # Project dependencies

```


## Planned Changes
It is planned to re-train the model to obtain higher accuracy after July 2025. 
