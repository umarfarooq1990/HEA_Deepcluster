# Deepcluster Agent

### Integrating Artificial Intelligence via Deep Reinforcement Learning for the Autonomous Discovery of High-Entropy Nanoclusters 



### How to Run the Code

1. **Set Up the Environment:**
   - Install the required Conda environment using the provided YAML file:
     ```bash
     conda env create -f Deepcluster.yml
     ```

2. **Configure the Nanocluster Composition:**
   - Edit `Deepcluster.py` to select the HEA nanocluster composition.

   For simulating a HEA cluster change 'eleNames' and 'eleNums':
   - **PdAgNiAu Nanocluster:** 
     ```python
     eleNames = ['Pd', 'Ag', 'Ni', 'Au']
     eleNums = [3,3,3,3]

     ```
   - **PdAgNiCu Nanoclusters:** 
     ```python
     eleNames = ['Pd', 'Ag', 'Ni', 'Au']
     eleNums = [3,3,3,3]
     
     ```

   - **PdAgNiPt Nanoclusters:** 
     ```python
     eleNames = ['Pd', 'Ag', 'Ni', 'Pt']
     eleNums = [3,3,3,3]
     ```
   - **PdAgCuAuPt Nanoclusters:** 
     ```python
     eleNames = ['Pd', 'Ag', 'Cu','Au', 'Pt']
     eleNums = [4,4,4,4,4]

     ```
3. **Run the Simulation:**
   - Execute the script using. 
     ```bash
     python Deepcluster.py  
