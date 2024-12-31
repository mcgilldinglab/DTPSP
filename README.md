# Deep Time Point Selector and Profiler (DTPSP)
DTPSP is a machine learning model for selecting optimal time points in single-cell analysis. The goal is to maximize the information learned from single-cell experiments by predicting the most informative time points for data collection. The model uses features derived from gene expression data to inform decision-making.

![Alt text](fig1_GitHub.png)

## Overview
- Predicts optimal time points for single-cell analysis.
- Supports pseudobulk and bulk RNA-seq data preprocessing.
- Uses a hybrid neural network for time series prediction.

## Example Use
To run the example code, please follow these steps:

1. **Download the Required Files**:  
   - Obtain the `Example_Code.ipynb` file and the `example_data` folder.

2. **Set Up the Computational Environment**:  
   - Ensure that Python and all required dependencies are installed. The necessary packages can be installed directly from within the notebook if not already available.

3. **Execute the Code**:  
   - Place the `example_data` folder in the same directory as the notebook.  
   - Open `Example_Code.ipynb` using Jupyter Notebook, Jupyter Lab, or Google Colab.  
   - Run the cells in the notebook sequentially to train the model and generate the outputs.

4. **Outputs**:  
   - The notebook will produce the trained model as well as average MAE and R<sup>2</sup> values.

These steps ensure reproducibility of the findings described in this work.

## License
This project is licensed under the GNU General Public License. See the `LICENSE` file for more details.
