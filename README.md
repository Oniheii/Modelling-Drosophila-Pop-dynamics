# Modelling Drosophila suzukii Population Dynamics for Pest Control

This repository contains the code and resources for a project focused on modeling the population dynamics of **Drosophila suzukii**, a pest species, with the aim of optimizing the use of the **Sterile Insect Technique (SIT)** for pest control. This technique has been widely researched to reduce pest populations in a sustainable and targeted manner.

### Project Overview

The primary objective of this project is to develop a mathematical model that simulates the population dynamics of Drosophila suzukii. The model is designed to:
- Incorporate biological and ecological characteristics of the species.
- Include stages of the life cycle (e.g., larvae, adult, etc.) and the effects of the SIT method.
- Provide insights into the efficiency of different SIT deployment strategies.

This work contributes to the broader effort of pest control through sustainable and non-chemical methods by leveraging advanced population dynamics models.

### Data and Methodology

The project relies on a combination of theoretical modeling and practical application through **Python** scripts. It includes:
- A **sex- and stage-structured population model** to simulate the growth and control of Drosophila suzukii populations.
- Parameterization based on **biological data** and field studies.
- Simulation of pest population dynamics over time with different SIT intervention scenarios.

The model evaluates the efficiency of **SIT** by simulating how sterile insect releases affect population suppression, taking into account different ecological and demographic parameters.

### Key Components

- **Modeling Framework**: The population model incorporates various biological stages and the effects of introducing sterile insects.
- **Python Scripts**: Python code (Jupyter Notebooks) used to run simulations and generate graphical outputs of population trends and SIT effectiveness.
- **Theoretical Analysis**: The model is backed by a theoretical analysis of population control dynamics, allowing for fine-tuned strategies.
  
### Results

Initial simulations suggest that the SIT can significantly reduce pest populations, but its success is highly dependent on the release strategy and environmental conditions. Further research can refine the model and explore optimal deployment strategies in various agricultural contexts.

### Next Steps

- Expand the model to include additional pest control methods and environmental variables.
- Conduct field validation of the model's predictions.
- Investigate the scalability of the model for other pest species and regions.

### File Structure

- `scripts/`: Contains Python scripts and Jupyter Notebooks for running simulations and generating output.
- `resources/`: Includes bibliographic resources, such as literature on the biology of Drosophila suzukii and mathematical modeling approaches.
- `outputs/`: Stores generated graphs and simulation results.
- `thesis_documents/`: Includes intermediate reports and final papers related to the project.

### How to Use

To run the model simulations, clone the repository and run the Python scripts in a Jupyter Notebook environment. All dependencies are listed in the `requirements.txt` file.
