# Plagiarism_Checker


## How to run (Command Line)
1. Download this repository and extract the file
2. Install required libraries

```bash
pip3 install -r requirements.txt
```
3. Run Plagiarism.py

```bash
$-> cd Plagiarism-checker-Python
$-> Plagiarism.py
```
3. Output

```bash
('john.txt', 'juma.txt', 0.5465972177348937)
('fatma.txt', 'john.txt', 0.14806887549598566)
('fatma.txt', 'juma.txt', 0.18643448370323362)

```

## How to run (Jupyter Notebook - Anaconda)
1. Download this repository and extract the file
2. Go to (https://www.anaconda.com/distribution/) and download anaconda 
3. Run the Script 
```javascript
 bash Anaconda3-2020.07-Linux-x86_64.sh
```  
4. Finalize the Installation Process (Choose Location)
5. Set Up Anaconda Environments
```javascript
 conda create --name user_environment python=3
 conda activate user_environment
``` 
6. Then go to terminal/cmd prompt and navigate to your project folder 
7. Run ('jupyter notebook') commenad
8. Open dataset and 'project.ipynb' file from folder
8. Pass the dataset path ('/home/Downloads/Projects/---.csv') and load the dataset into jupyter notebook
9. Run all blocks
