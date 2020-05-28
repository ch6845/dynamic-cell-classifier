

#




# Env setting 

```
conda create --name sc python=3.7
conda activate sc

conda install pytorch torchvision cudatoolkit=10.0 -c pytorch
conda install ipykernel numpy pandas scipy scikit-learn matplotlib
```

# Env setting (Optinal)

```
conda install ipykernel r-base=3.6.0
```

```
install.packages('IRkernel')
IRkernel::installspec()
```
```
conda install -c bioconda bioconductor-biocinstaller
```
```
install.packages('Seurat')
library(Seurat)
install.packages("devtools")
devtools::install_github("BaderLab/scClustViz")
```

```
install.packages("tensorflow")
tensorflow::install_tensorflow(extra_packages='tensorflow-probability', version = "2.1.0")
install.packages("devtools") # If not already installed
devtools::install_github("Irrationone/cellassign")
```