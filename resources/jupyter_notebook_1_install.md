# Jupyter Notebook:  Getting Started
The Jupyter notebook is an interactive computational environment, in which you can combine code, execution, rich text, mathematics, plots and rich media. 

---

### [Install the Notebook](http://jupyter.readthedocs.io/en/latest/install.html)
Installing Jupyter using Anaconda and conda:  
For new users, we highly recommend [installing Anaconda](https://www.continuum.io/downloads). Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.  (Prereq: Python is installed.)

Once anaconda is installed, you can launch the notebook by typing
```{bash}
$ jupyter notebook
```

### Upgrade all libraries/packages
We will now update all the packages/libraries installed by anaconda to ensure you have the latest version of everything!

```{bash}
$ conda update --all
```

### Run the Notebook at Terminal Prompt  
Note:  The notebook will open at the directory in which you launch the notebook on your terminal.  
```
$ jupyter notebook
```
[I 14:08:17.879 NotebookApp] Writing notebook server cookie secret to /run/user/1000/jupyter/notebook_cookie_secret
[I 14:08:18.603 NotebookApp] JupyterLab beta preview extension loaded from /home/pnietoramos/anaconda3/lib/python3.6/site-packages/jupyterlab
[I 14:08:18.603 NotebookApp] JupyterLab application directory is /home/pnietoramos/anaconda3/share/jupyter/lab
[I 14:08:18.621 NotebookApp] Serving notebooks from local directory: /home/pnietoramos
[I 14:08:18.621 NotebookApp] 0 active kernels
[I 14:08:18.622 NotebookApp] The Jupyter Notebook is running at:
[I 14:08:18.622 NotebookApp] http://localhost:8888/?token=0c4b0d0d7647d111a54501a1ffbe318587a7617ba915b026
[I 14:08:18.622 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).

```console
reshama$ jupyter notebook
[I 11:41:22.769 NotebookApp] Serving notebooks from local directory: /Users/reshamashaikh/_ds/metis
[I 11:41:22.769 NotebookApp] 0 active kernels 
[I 11:41:22.769 NotebookApp] The Jupyter Notebook is running at: http://localhost:8888/
[I 11:41:22.769 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
```

### Shut Down the Juypter Notebook App
At terminal prompt:  
 * control + c
 * type:  `y`
 
^C[I 14:24:59.379 NotebookApp] interrupted
Serving notebooks from local directory: /home/pnietoramos
1 active kernel
The Jupyter Notebook is running at:
http://localhost:8888/?token=0c4b0d0d7647d111a54501a1ffbe318587a7617ba915b026
Shutdown this notebook server (y/[n])? y
[C 14:25:03.698 NotebookApp] Shutdown confirmed
[I 14:25:03.699 NotebookApp] Shutting down 1 kernel
[I 14:25:04.101 NotebookApp] Kernel shutdown: 4ab9187a-e0b0-44f6-a590-b297abc9e167

```console
^C[I 11:43:35.486 NotebookApp] interrupted
Serving notebooks from local directory: /Users/reshamashaikh/_ds/metis
0 active kernels 
The Jupyter Notebook is running at: http://localhost:8888/
Shutdown this notebook server (y/[n])? y
[C 11:43:37.782 NotebookApp] Shutdown confirmed
[I 11:43:37.783 NotebookApp] Shutting down kernels
reshama$ 
```

---

### Getting to Know Jupyter

You can try out Jupyter on a browser without installing it.  
https://try.jupyter.org/

