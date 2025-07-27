# TorontoMetMRP-Results

To run these notebooks successfully, please follow the instructions below:

EDA Portion:

This coding portion was done in Jupyter Notebook.

1. Download the MRP_EDA.ipynb file
2. Download the Olist Dataset from the following link: https://www.kaggle.com/datasets/erak1006/brazilian-e-commerce-company-olist/data
3. Create a local directory
4. In the same directory where you upload the .ipynb file, create a folder called: Dataset
5. Place all the data files into said folder
6. Launch the notebook, and run each cell block in sequence
7. The last cell block will save the merged and clean dataset required for the next portion in the same folder as MRP_EDA.ipynb.

Modeling and Results portion:

This was done in Google Colaboratory. If possible, change the runtime type to one of the GPUs to save on time (I used the A100 GPU).

1. Download the merged and clean dataset, merged_eda_output.csv.
2. Download the MRP_RESULTS.ipynb
3. Place them both in a folder in your Google Drive.
4. Right Click on MRP_RESULTS and open with Google Colab.
5. The first cell block has all the required pip installs commented. Please pip install them all, then run the imports block.
6. Run the second cell block to connect to your google drive.
7. Edit the third cell block to the file path where the merged dataset exists, then run it. (Ex: mine is file_path = '/content/drive/MyDrive/MRP/merged_eda_output.xls')
8. Once all the above are complete, you can run all the remaining cell blocks.

Thank you!
