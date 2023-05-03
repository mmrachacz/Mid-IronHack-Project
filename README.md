# __Temperature Change in the EU__              
*by Maximilian Mrachacz*                            
*for IronHack Remote Bootcamp Data Analytics*             
                  
## Overview:               
Finding parameters that (might) have an impact on / drive Temperature Change.     
Final Version: [New_Version_Temp_Change_and_other](https://github.com/mmrachacz/Mid-IronHack-Project/blob/main/New_Version_Temp_Change_and_other.ipynb)        
                
### Tools and Methods Used:               
                 
    - Python               
    - Statistical analysis             
    - Data visualization              
    - Jupyter Notebook              
    - Tableau             
    - Machine Learning (Logistic Regression)                
    - About the Dataset:              
    - Data is about Temperature Change and Factors that might be correlated.                
                  
### Sources:                    

    - https://www.fao.org/faostat/en/#data               
    - http://data.un.org/Explorer.aspx             
    - Final Dataset/DataFrame:              
         
### [About New_Version_Temp_Change_and_other.ipynb:](https://github.com/mmrachacz/Mid-IronHack-Project/blob/main/New_Version_Temp_Change_and_other.ipynb)      
         
    - 838 rows × 14 columns                 
    - created by merging 10 sub- tables together             
    - columns hold exactly the information as what there called              
    - last two (predicted) columns come from prediction with GradientBoostingRegressor              
    - tried different models, compared precision, decided on used model          
    - for prediction, 2 new dataset were created with manufactured data values     
              
### Data Cleaning:           
              
    - dropping columns       
    - converting numbers         
    - merging, renaming           
    - filling NaNs (mostly by KNeighbor Regression)          
    - using 3 neighbors     
                   
### Data Storage:            
       
    - Saved data as .csv file               
       
### Visualization: [Tableau](https://public.tableau.com/app/profile/max.mrachacz/viz/finalproject_16796675233000/predictions)      
    
### Presentation: [Prezi](https://prezi.com/view/ISR0Yf2hNeyc9SSx1D6Y/)          
           
### Conclusion:           

    - The Parameters that were examined suggest correlations with the rise of average temperatures. 
    - For better prediction result, more Parameters are needed
