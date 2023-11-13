# QML_Hardware_Optimization
## Overview
This repository contains a quantum machine learning project focused on developing an optimal quantum algorithm for a binary classification task, tailored for a specific quantum computer architecture. The project utilizes an evolutionary algorithm for algorithm generation.

## Files
* **encoding.py**: Implements functions for encoding a quantum state in amplitude.<br />
* **generate_dataset.py**: Generates a dataset of strips and wipes for training the quantum algorithm.<br />
* **generating_circuit.py**: Provides functions for generating a quantum circuit.<br />
* **main.py**: Main script that creates the quantum algorithm scheme and performs the learning process.<br />
* **performance_testing.py**: Conducts performance testing of the quantum circuit.<br />
* **qiskit_encoding.py**: Includes functions for encoding using Qiskit.<br />
## How It Works
### Encoding Quantum States
The **encoding.py** module handles the task of encoding quantum states in amplitude. It plays a crucial role in preparing the input data for the quantum algorithm.

### Dataset Generation
The **generate_dataset.py** script generates a dataset of strips and wipes. This dataset is used for training the quantum algorithm.

### Quantum Circuit Generation
The **generating_circuit.py** module is responsible for generating the quantum circuit. It leverages the encoded quantum states and constructs the necessary layers for the classification task.

### Main Algorithm Implementation
The **main.py** script brings everything together. It creates the quantum algorithm scheme and executes the learning process. This is where the evolutionary algorithm is applied to optimize the quantum circuit for the specific hardware.

### Performance Testing
The **performance_testing.py** script assesses the performance of the quantum circuit. It provides insights into the accuracy and efficiency of the trained quantum algorithm.

### Qiskit Encoding
The **qiskit_encoding.py** file includes functions for encoding using Qiskit. This is particularly relevant for interfacing with Qiskit-based quantum hardware.

## Project Focus: Optimizing for Given Quantum Architecture
Hardware-Centric Algorithm Development
The project emphasizes a hardware-centric approach to algorithm development. Rather than retrofitting existing algorithms to the hardware, it designs algorithms from the ground up. This approach ensures that the unique capabilities and limitations of our quantum hardware are considered, resulting in superior performance and efficiency.
