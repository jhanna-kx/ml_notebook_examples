# Machine Learning Demonstrations 

This repository contains notebooks that illistrate different machine learning algorithms using embedPy.

1. Neural networks (NN notebook)
2. Dimensionality Reduction
3. K-nearest Neighbours
4. Feature Engineering (NN notebook)
5. Decision Trees
6. Random Forests
   

## Docker

If you have [Docker installed](https://www.docker.com/community-edition) you can create a directory called `q` and place your `kc.lic` (or `k4.lic`) and `l64.zip` files into a `q` directory and run:

```
    docker run --rm -it -v `pwd`/q:/tmp/q -p 8888:8888 kxsys/ml_notebook_examples
 ```

Now point your browser at http://localhost:8888/tree/notebooks

**N.B.** [build instructions for the image are available](docker/README.md)

## Installation

These are the steps that are required to run the notebooks:

1. Install Q (version 3.5 or higher/64-bit)
   * make sure q is on the path 
   * set QHOME
   * also see https://code.kx.com/q/tutorials/install/


2. Install Anaconda-Python(version 3.5 or higher)
   * see https://conda.io/docs/user-guide/install/index.html

**Steps 3 and 4 are only required to run Neural Network Notebooks**

3. Install Cuda (version 9.0)
   * see https://developer.nvidia.com/cuda-90-download-archive


4. Install tensorflow
   * see https://www.tensorflow.org/install/ 


5. Install embedPy
   * see https://github.com/KxSystems/embedPy

6. Install jupyterq
   * see https://github.com/KxSystems/jupyterq
   * Check if the kdb+ notebook works

7. Install required python packages 
   * Common modules in Graphics.q
      * numpy
      * matplotlib

   * Neural Networks:
      * Keras
      * scikit-learn

   * Dimensionality reduction:
      *  numpy
      *  matplotlib
      *  Keras
      *  scikit-learn

   * K-Nearest Neighbours:
      * scikit-learn
      * numpy
      * matplotlib

   * Feature Engineering:
      * scikit-learn
      * Keras
      * numpy
      * matplotlib

   * Decision trees:
      * numpy
      * scipy
      * graphviz
      * matplotlib
      * scikit_learn
      * xgboost
        
   * Random Forest:
       * numpy
       * pandas
       * scikit_learn
       * xgboost


   To install these packages run this line in the terminal: 
   
   ```bash
    pip install -r requirements.txt
   ```
   
