# How to use conda on windows

1. For easily installing python packages on windows install [miniconda](https://conda.io/miniconda.html).

2. Open search and search for anaconda as follows:
   ![image](https://i.stack.imgur.com/I0Kx2.png)

3. Click on Anaconda Prompt, this will open a Anaconda command line for windows as given below:
    ![image](https://i.stack.imgur.com/gReS1.png)

4. For installing package named **pycrypto** write the command

```
conda install -c anaconda pycrypto
```

   as given [here](https://anaconda.org/anaconda/pycrypto). In this way pycrypto is installed using conda in windows environment:
   ![image2](https://i.stack.imgur.com/6S8BQ.png)

5. To execute a script using anaconda in windows, first get the current working directory used by conda on your system using:

```
import os
os.getcwd()
```
  This will give the current working directory as shown below:
  ![image4](https://i.stack.imgur.com/xtgXa.png)

6. Then come out of python compiler into anaconda command line using:
  
  ```
  import sys
  sys.exit()
  ```
  
   ![image5](https://i.stack.imgur.com/RASyp.png)
 
 7. Put your code in current working directory as shown below:
   
   ![image6](https://i.stack.imgur.com/k5xFD.png)
   
 8. Now execute this code using anaconda command line as shown below:
   
    ![image7](https://i.stack.imgur.com/AUO4J.png) 
  This concludes the tutorial for installing packages and compiling python code using conda on windows.

   
