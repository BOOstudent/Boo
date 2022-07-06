# Boo
All files created during the Boo period

### Overview of the project
This code is used to evaluate the influence of several molecular descriptors and dimension reduction on chemical space.
This project is part of my bachelor end project at Leiden university, at the computational drug discovery group at the LACDR. The purpose of this project was to see what differences could be observed in the chemical space of chemokine receptor ligands when different types of molecular descriptors and dimension reduction methods where used. 
By using molplotly, interactive scatterplots are created and the compounds are coloured based on their scaffolds. 

![image](https://user-images.githubusercontent.com/105792139/176861292-c6fc446a-1abf-41e4-95c5-18ef7d6e497f.png)


### File structure
[data_filter.ipynb](data_filter.ipynb) is used to select a subset of data from the Papyrus database.
[calculating_descriptors.ipynb](calculating_descriptors.ipynb) is used to calculate 2D descriptors, morgan fingerprints and pharmacophore fingerprints of the data.
[calculating_3D_descriptor.ipynb](calculating_3D-descriptors.ipynb) is used to calculate the 3D descriptors
[PCA.ipynb](PCA.ipynb) contains the code for the principal component analysis on the data.
[MDS.ipynb](MDS.ipynb) contains the code for the multidimensional scaling on the data.
[ISOmap.ipynb](ISOmap.ipynb) contains the code for the ISOmap on the data.
[UMAP.ipynb](UMAP.ipynb) contains the code for the UMAP on the data.
[t-SNE.ipynb](t-SNE.ipynb) contains the code for t-SNE on the data.

All the dimension reducrtion files are present for the CCR5 ligand data as well. 

