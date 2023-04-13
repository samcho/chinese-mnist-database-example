# Chinese MNIST CNN Jupyter Notebook 

<img src="https://i.redd.it/us20649d73wz.jpg" alt="I don't know, I don't speak Chinese." width="250"/>

1. Log into your machine using the following command:
```
ssh -L 8888:localhost:8888 username@username.greenflash.cs.wfu.edu
```

2. Clone this repository:
```
git clone git@github.com:samcho/chinese-mnist-database-example.git
```

This repository contains the Chinese MNIST dataset in a zipped file named archive.zip to save space.

3. Unzip the Chinese MNIST dataset
```
cd chinese-mnist-database-example
unzip archive.zip
```

You must also ensure that all of the libraries imported by the Jupyter notebook are present.

4. Install the prerequisite libraries:
```
pip install requirements.txt 
```

Now go back to your home directory and start your Jupyter Notebook

5. Start Jupyter notebook on your greenflash machine:
```
source jupyter/bin/activate
jupyter notebook password
jupyter-notebook
```

6. In your browser on your host machine (e.g., laptop), enter:
```
http://localhost:8888
```
