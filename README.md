# LT-PINN: Lagrangian Topology-conscious Physics-informed Neural Network for Boundary-Focused Engineering Optimization

## How to Use the Code

### Step 1: Unzip the LT-PINN.zip File

The files are organized as follows:

LT-PINN/

├── data/
|  ├── heat_128x128.csv
|  └── solid.csv
├── DT/
|  ├── checkpoint/
|  └── code/
|     ├── loss.py
|     ├── main.py
|     └── NeuralNetwork.py
└── LT/
   ├── checkpoint/
   └── code/
       ├── loss.py
       ├── main.py
       └── NeuralNetwork.py



### Step 2: Navigate to the Code Directory and Start Training

1. **Navigate to the Code Directory**:
   - Open your terminal or command prompt.
   - Change to the directory containing the `main.py` file. For example:
     ```bash
     cd path/to/LT-PINN/DT/code
     ```

2. **Run the Training Script**:
   - Execute the `main.py` script to start training:
     ```bash
     python main.py
     ```

### Additional Notes

- **Dependencies**: Ensure you have the necessary Python packages installed. You can install them using `pip`:
  ```bash
  pip install numpy matplotlib torch
