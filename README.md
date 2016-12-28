# Ipython-notebooksetup-mac
Set up guidelines for ipython notebook set up with python 2.7 version step by step. 
# Download miniconda
1. http://conda.pydata.org/miniconda.html <br />
This should be downloaded into your downloads folder. <br />
2. Go to your download folder from terminal by <br />
```
cd Downloads
```
3. run the downloaded sh script Mini........sh <br />
```
bash MIni.......sh
```

# Create a new environment for different version of python
```
conda create -n yourenvname python=2.7
```
# Install packages you need
```
conda install numpy   #it will install numpy
conda install scipy    #it will install scipy
conda install ipython-notebook #it will install ipython-notebook
```
# Install graphlab
```
pip install graphlab-create
```

