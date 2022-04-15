# Python_Project_Template
Python | Project | Template


## STEPS -

### STEP 01- Create a Folder in Local PC

### STEP 02- Clone the new repository
```bash
git clone https://github.com/mdnazmulislam0087/Transfer_learning_demo.git
```

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.7 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05- To see base model training for MNIST DATA write
```bash
python src/01_base_model_creation.py

```
### STEP 06- To see base model training for EVEN and ODD from MNIST DAta write
```bash
 python src/02_transfer_learning_even_odd_case.py

```
### STEP 07- To see base model training for Less than and Greater than 5s from MNIST DAta write
```bash
 python src/03_greater_than_5_and_less_than_5.py

```