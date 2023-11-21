# Fraud-Detection
The project is developed on the Intel OneAPI platform, utilizing Intel's **modin** module, the **Intel® Extension for Scikit-learn**, and the **Intel-optimized XGBoost tool**. The investigation focuses on the method accuracy in predicting credit card fraud and assesses the acceleration effects of the Intel tools.

**The procedure of running this project**

- First, you can  clone this project to your local computer by the command:

  ```
  git clone 
  ```

- And then, you have to login/register(if you don't have an account) on https://devcloud.intel.com/oneapi/get_started/ ,  after that please launch JupyterLab 

​	<img src="C:\Users\74236\AppData\Roaming\Typora\typora-user-images\image-20231121203840058.png" alt="image-20231121203840058" style="zoom:40%;" />

- Upload the project you have cloned just now, and run these commands to install relevant environments:

  ```bash
  pip install "modin[dask]" # Install Modin dependencies and Dask.
  export MODIN_ENGINE=dask  # Modin will use Dask
  
  pip install scikit-learn-intelex
  pip install seaborn
  ```

  if you use conda to manage your package, please change pip as conda
