# IC-Scalar_on_function
Study for my undergraduate research where it consists of studying regression models with scalar response 
variable and functional covariables using the fda and refund packages. The data was collected from
336 preagnant woman during the prenatal evaluations for a study from the Hospital das Clínicas da Faculdade
de Medicina da Universidade de Sao Paulo (FMUSP).

# The database "Base_TocoColoPerinatal.xls" is the original of this study, it contains missing data, and
the prenatal evaluations are interpreted as having been made every two weeks, resulting in 5 prenatal
evaluations. 

# The database "datas_igs_completas.xlsx" is the modified database, the MICE data imputation 
method was applied in this one, besides that, the evaluations of the functional covariates were 
interpreted as having been made every week, resulting in 11 evaluations in the prenatal period. 

# For each approach of the study there is a "object.RData" with all the objects of the script for that
specific approach, you can choose run the entire scrip or just load the objects.
