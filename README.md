# scHFC

We present the hybrid fuzzy clustering (scHFC), a hybrid fuzzy clustering method to cluster cells from scRNA-Seq data. scHFC combines FCM and Gath-Geva two fuzzy clustering method, which can detect clusters robustly with varying shapes. In addition, FCM is optimized by simulated annealing algorithm (SA) and genetic algorithm (GA),which improves clustering performance and stability of algorithm simultaneously.   

See details in our paper: "A hybrid fuzzy clustering method for single-cell RNA-Seq data optimized by natural computation".  
   
Quick start:  
Download the the Matlab Toolbox for Dimensionality Reduction(version 0.8b) and code files in this repository and import functions in them.  
1.Prepare datasets  
scHFC takes preprocessed data as input. Single cell data preprocessing can be done with preprocessing data.r.  
2.Download and load the Matlab Toolbox in MATLAB. 
3.Run scHFC algorithm 
Run the algorithm with scHFCmain.m function.  
4.Compute clustering indexes with compute index.py.  



Requirements: 
Matlab---2014a
python---3.8.5 
numpy --- 1.18.5  
pandas --- 1.1.3 
h5py ---2.10.0
scanpy---1.7.1  
scikit-learn --- 1.0.1
matplotlib --- 3.3.2
   
If you have any questions, please contact me. 
e-mail: jingwang319@126.com.