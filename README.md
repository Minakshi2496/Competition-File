**Steps to run code**

1. First download Python

2. Go to your browser-> type python-> Download latest version from www.python.org/downloads/ -> Install it on your machine

3. To check if python is installed on machine-> type cmd on window search-> type py and enter-> it will show the result

4. Again go to your browser-> type anaconda-> Download anaconda individual edition from www.anaconda.com/products/individual -> Install it on your machine

5. To check if anaconda is installed on machine-> type anaconda on window search-> open anaconda navigator

6. Type Jupyter notebook on window search -> Click on Jupyter Notebook -> Jupyter Notebook will open on your browser

7. Once the jupyter is opened on your browser, open a new python file by clicking on 'new' tab and then click on 'python3'

8. Open the code file(Class Reproduce.ipynb) on github  or Click on the link https://github.com/Minakshi2496/Competition-File/blob/main/Class%20Reproduce.ipynb 

9. The link will take you to the code file, copy the code from the file and paste it in jupyter notebook

10. Before running the code enter your dataset  file path in the 4th line of the code where training dataset is loaded

11. Do same for loading gene_names file in next line. Enter the path to gene_names file

For example: on our machine the dataset was in ‘Download’ folder in ‘My Computer’. Therefore, the path we used is  "C:\Users\vineet\Downloads\data_tr.txt" for dataset and "C:\Users\vineet\Downloads\gene_names.txt" for gene names

12. Run the code and it will give the clusters in predictions2 variable

13. If you are passing the predictions to the API you must convert the predictions into list using predictions2.tolist() 

14. For instance -> payload = json.dumps(predictions2.tolist())
