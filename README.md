# Quantum Error Correction Simulator

The **Quantum Error Correction Simulator** is a software tool designed to simulate and visualize quantum error correction processes. It integrates various components to allow users to configure, run, and analyze quantum simulations effectively. A key feature here is quick quantum circuit diagram creation through LaTeX integration.
![image](https://github.com/user-attachments/assets/1b92b7d6-7bcf-4c60-a319-4ff769680a63)


## **Functionality**

- **Parameter Configuration**
  - **Lattice Size (NxN):** User inputs the size of the quantum lattice.
  - **Error Rate:** User specifies the probability of errors occurring.
    
    ![image](https://github.com/user-attachments/assets/dc56d827-3d09-4ca6-a7fd-2e053ba11080)

  - **Error Type:** Options include Bit-flip, Phase-flip, and Depolarizing errors.
    
    ![image](https://github.com/user-attachments/assets/b16acf09-7e06-4ff8-aad5-019812258af2)

  - **Visualization Style:** Choices include Coolwarm, Viridis, and Plasma colormaps.
  - **Error Correction Algorithm:** Options are None, Shor Code, and Steane Code.
    
    ![image](https://github.com/user-attachments/assets/13d43dfc-b3b9-4f28-8d60-242d6d6ad465)


- **Simulation Execution**
  - Constructs the quantum circuit based on input parameters.
  - Applies Hadamard and CNOT gates to initialize the lattice.
  - Injects errors according to the specified error rate and type.
  - Applies selected error correction algorithms.
  - Measures stabilizers before and after error correction.
  - Runs the simulation and collects results.

    ![image](https://github.com/user-attachments/assets/5d9a6bbb-0863-4db1-b06c-79d99cf9b23c)


- **Visualization Options**
  - **Lattice Before / After Error Correction:** Displays state of the lattice before and after using a correction algorithm.
    
    ![image](https://github.com/user-attachments/assets/a94506f0-8e47-43d6-9f11-a7faf3dbef17)

  - **Measurement Results:** Shows the outcomes of quantum measurements.
  - **Qubit State Probabilities:** Visualizes the probabilities of qubit states.

    ![image](https://github.com/user-attachments/assets/c77c76eb-0241-42af-a8c5-b9912ea9b0d9)

  - **Circuit Diagram:** Generates a diagram of the quantum circuit used.
 
    ![image](https://github.com/user-attachments/assets/329276d5-42f2-4ce3-b7b1-8493e5e475dc)



## **Technical Specifications**

- **Programming Language:** Python
- **Libraries and Frameworks:**
  - *Cirq:* For quantum circuit construction and simulation.
  - *PyQt5:* For building the graphical user interface.
  - *Matplotlib:* For creating visualizations.
  - *NumPy:* For numerical operations.
  - *JSON:* For data serialization and storage.
