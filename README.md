# A Machine Learning Framework to Antimicrobial Resistance Prediction and Characterization of AMR-Related SNPs in *Mycobacterium tuberculosis*
### Brief overview
In this study, we applied this machine learning (ML) framework to predict resistance phenotypes for 12 anti-tuberculosis drugs while outputting SNPs associated with resistance. Then, the SHapley Additive exPlanations (SHAP) framework was used to decipher why and how decisions were made in the optimal algorithm. Lastly, we applied the models to predict the resistance phenotype to rifampicin (RIF) and isoniazid (INH) in an additional independent *Mycobacterium tuberculosis* isolates dataset from India.
### Programming codes
These are the programming codes used in our paper "A Machine Learning Framework to Antimicrobial Resistance Prediction and Characterization of AMR-Related SNPs in *Mycobacterium tuberculosis*". 

### Get Started
Follow these steps to install packages and run the examples.

### Technical Stack
- Language: Python=3.8.15; R=4.0
- Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, shap, etc.
- Tools: Jupyter Notebook; Rstudio
  
### Step 1: Ensure Jupyter Notebook and Conda are Installed
First, you need to ensure that ○ [Jupyter Notebook](https://jupyter.org/install) and ○ [Miniconda](https://docs.anaconda.com/miniconda/) or ○ [Anaconda](https://www.anaconda.com/download/) are installed in your system. 


### Step 2: Create a virtual environment and Install Packages from env/files
#### Build the Projects 
##### First, clone this repository to your local machine:
```bash
git clone https://github.com/microbial123/MTB-AMR-Programming-codes-0826.git
cd MTB-AMR-Programming-codes-0826
```

#### Method: 
```bash
cd MTB-AMR-Programming-codes-0826/env
conda env create -f AMR_env.yml
```


### step3: Launch Jupyter Notebook and Specify the AMR_env Kernel

```
conda activate AMR_env
# assure ipykernel is installed.
# conda install ipykernel
# Register this AMR_env as a kernel for Jupyter Notebook.
python -m ipykernel install --user --name AMR_env --display-name "AMR_env" 
```

### Step4: Run the workflow:
Start Jupyter Notebook in your system :
```bash
jupyter notebook
```
Open the notebook: Navigate to **Figure_2.ipynb**.<br>

Execute the notebook: Run all cells in order.<br>

#### Select "Kernel" from the menu, then choose "Change kernel". From the list, select "AMR_env".

![select "AMR_env"](https://github.com/microbial123/MTB-AMR-Programming-codes-0826/blob/main/env/env_kernel.png)


### Note: You can adjust the number "n_jobs=16" flexibly based on your system! 


### Figure2_Input
>./Data/rifampicin.csv
./Data/rifampicin_to_predict_MTB.csv

### Figure2_Output

>./Figure2/All_fold6_rst/ML_Plot_MTB_rifampicin_6-fold_CV.tiff
./Figure2/All_fold6_rst/MTB_rifampicin_All_Set_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_All_Set_Performance_Training_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_All_Set_Test_Area_Under_Precision_Recall_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_All_Set_Test_Area_Under_ROC_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_All_Set_Test_Training_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_All_Set_Tf_CV_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Complete_Results_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Consistent_Genes_Per_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_F1_comparision_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Intersect_Set_Performance_Area_Under_Precision_Recall_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Intersect_Set_Performance_Area_Under_ROC_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Intersect_Set_Performance_Test_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Intersect_Set_Performance_Training_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Intersect_Set_Tf_CV_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Intersection_Set_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Random_Set_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Random_Set_Performance_Tf_CV_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Random_Set_Performance_Training_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Random_Set_Test_Area_Under_Precision_Recall_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Random_Set_Test_Area_Under_ROC_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Random_Set_Test_Loo_CV_6-fold_CV.csv
./Figure2/All_fold6_rst/MTB_rifampicin_Random_Set_Test_Training_Performance_6-fold_CV.csv
./Figure2/All_fold6_rst/rifampicin_ABC.sav
./Figure2/All_fold6_rst/rifampicin_BC.sav
./Figure2/All_fold6_rst/rifampicin_DT.sav
./Figure2/All_fold6_rst/rifampicin_ETC.sav
./Figure2/All_fold6_rst/rifampicin_GBC.sav
./Figure2/All_fold6_rst/rifampicin_KNN.sav
./Figure2/All_fold6_rst/rifampicin_LDA.sav
./Figure2/All_fold6_rst/rifampicin_LogR.sav
./Figure2/All_fold6_rst/rifampicin_RF.sav
./Figure2/All_fold6_rst/rifampicin_SVM.sav
./Figure2/All_fold6_rst/rifampicin_gNB.sav
./Figure2/All_fold6_rst/rifampicin_mNB.sav

./Figure2/Figure_2A.tiff
./Figure2/Figure_2Bi.png
./Figure2/Figure_2Bii.png
./Figure2/Figure_2Biii.png
./Figure2/Figure_2Biv.png

### Running the Code
```bash
cd MTB-AMR-Programming-codes-0826/Figure3
```
Open the notebook: Navigate to **Figure_3.ipynb**.<br>
Execute the notebook: Run all cells in order.<br>

### Switch the environment to the AMR_env kernel.
![manually select "AMR_env" kernel](https://github.com/microbial123/MTB-AMR-Programming-codes-0826/blob/main/env/Figure3.png)

### Figure3_Input1

### Top15_Trainind data
>./Data/ethambutol_Top15.csv
./Data/isoniazid_Top15.csv
./Data/pyrazinamide_Top15.csv
./Data/rifampicin_Top15.csv

### Top15_To_predict data
>./Data/ethambutol_Top15_to_predict_MTB.csv
./Data/isoniazid_Top15_to_predict_MTB.csv
./Data/pyrazinamide_Top15_to_predict_MTB.csv
./Data/rifampicin_Top15_to_predict_MTB.csv


### Figure3_Output1
### Top15_model
>./Figure3/Top15_model/ethambutol_ABC_Top15.sav
./Figure3/Top15_model/ethambutol_BC_Top15.sav
./Figure3/Top15_model/ethambutol_DT_Top15.sav
./Figure3/Top15_model/ethambutol_ETC_Top15.sav
./Figure3/Top15_model/ethambutol_GBC_Top15.sav
./Figure3/Top15_model/ethambutol_KNN_Top15.sav
./Figure3/Top15_model/ethambutol_LDA_Top15.sav
./Figure3/Top15_model/ethambutol_LogR_Top15.sav
./Figure3/Top15_model/ethambutol_RF_Top15.sav
./Figure3/Top15_model/ethambutol_SVM_Top15.sav
./Figure3/Top15_model/ethambutol_gNB_Top15.sav
./Figure3/Top15_model/ethambutol_mNB_Top15.sav
./Figure3/Top15_model/isoniazid_ABC_Top15.sav
./Figure3/Top15_model/isoniazid_BC_Top15.sav
./Figure3/Top15_model/isoniazid_DT_Top15.sav
./Figure3/Top15_model/isoniazid_ETC_Top15.sav
./Figure3/Top15_model/isoniazid_GBC_Top15.sav
./Figure3/Top15_model/isoniazid_KNN_Top15.sav
./Figure3/Top15_model/isoniazid_LDA_Top15.sav
./Figure3/Top15_model/isoniazid_LogR_Top15.sav
./Figure3/Top15_model/isoniazid_RF_Top15.sav
./Figure3/Top15_model/isoniazid_SVM_Top15.sav
./Figure3/Top15_model/isoniazid_gNB_Top15.sav
./Figure3/Top15_model/isoniazid_mNB_Top15.sav
./Figure3/Top15_model/rifampicin_ABC_Top15.sav
./Figure3/Top15_model/rifampicin_BC_Top15.sav
./Figure3/Top15_model/rifampicin_DT_Top15.sav
./Figure3/Top15_model/rifampicin_ETC_Top15.sav
./Figure3/Top15_model/rifampicin_GBC_Top15.sav
./Figure3/Top15_model/rifampicin_KNN_Top15.sav
./Figure3/Top15_model/rifampicin_LDA_Top15.sav
./Figure3/Top15_model/rifampicin_LogR_Top15.sav
./Figure3/Top15_model/rifampicin_RF_Top15.sav
./Figure3/Top15_model/rifampicin_SVM_Top15.sav
./Figure3/Top15_model/rifampicin_gNB_Top15.sav
./Figure3/Top15_model/rifampicin_mNB_Top15.sav
./Figure3/Top15_model/pyrazinamide_ABC_Top15.sav
./Figure3/Top15_model/pyrazinamide_BC_Top15.sav
./Figure3/Top15_model/pyrazinamide_DT_Top15.sav
./Figure3/Top15_model/pyrazinamide_ETC_Top15.sav
./Figure3/Top15_model/pyrazinamide_GBC_Top15.sav
./Figure3/Top15_model/pyrazinamide_KNN_Top15.sav
./Figure3/Top15_model/pyrazinamide_LDA_Top15.sav
./Figure3/Top15_model/pyrazinamide_LogR_Top15.sav
./Figure3/Top15_model/pyrazinamide_RF_Top15.sav
./Figure3/Top15_model/pyrazinamide_SVM_Top15.sav
./Figure3/Top15_model/pyrazinamide_gNB_Top15.sav
./Figure3/Top15_model/pyrazinamide_mNB_Top15.sav

### Figure3_Input2
### India_To_predict_data
>./Figure3/Data_to_predict/India_ethambutol_to_predict_MTB_166.csv
./Figure3/Data_to_predict/India_isoniazid_to_predict_MTB_166.csv
./Figure3/Data_to_predict/India_pyrazinamide_to_predict_MTB_166.csv
./Figure3/Data_to_predict/India_rifampicin_to_predict_MTB_166.csv

>./Figure3/Data_to_predict/India_ethambutol_to_predict_MTB_166_sort.csv
./Figure3/Data_to_predict/India_isoniazid_to_predict_MTB_166_sort.csv
./Figure3/Data_to_predict/India_pyrazinamide_to_predict_MTB_166_sort.csv
./Figure3/Data_to_predict/India_rifampicin_to_predict_MTB_166_sort.csv

### True phenotype of 166 India Isolates
>./Figure3/Data_to_predict/India_ethambutol_Top15_phenotype.txt
./Figure3/Data_to_predict/India_isoniazid_Top15_phenotype.txt
./Figure3/Data_to_predict/India_pyrazinamide_Top15_phenotype.txt
./Figure3/Data_to_predict/India_rifampicin_Top15_phenotype.txt


### Figure3_Output2
>./Figure3/Data_to_predict_rst/rst_India_ethambutol_to_predict_MTB.csv
./Figure3/Data_to_predict_rst/rst_India_isoniazid_to_predict_MTB.csv
./Figure3/Data_to_predict_rst/rst_India_pyrazinamide_to_predict_MTB.csv
./Figure3/Data_to_predict_rst/rst_India_rifampicin_to_predict_MTB.csv

>./Figure3/Data_to_predict_rst/ethambutol_predict_rst_12model.csv
./Figure3/Data_to_predict_rst/isoniazid_predict_rst_12model.csv
./Figure3/Data_to_predict_rst/pyrazinamide_predict_rst_12model.csv
./Figure3/Data_to_predict_rst/rifampicin_predict_rst_12model.csv

### merge all predict_rst_12model.csv to Table_S6.xlsx
>./Figure3/Table_S6.xlsx


### Running the Code
```bash
cd MTB-AMR-Programming-codes-0826/Figure3
```
Open the Rstudio: Navigate to **./Figure3/Figure3A.R**<br>
Execute the Rstudio: Run the scripts.<br>

### Figure3_Output3
>./Figure3/Figure3A.pptx

Open the Rstudio: Navigate to **./Figure3/Figure3C.R** <br>
Execute the Rstudio: Run the scripts.<br>
### Figure3_Output3
>./Figure3/Figure3C.pptx
<br>
<br>
<br>

#### For any questions or issues, please contact Mao at microbial_research@163.com.<br>
