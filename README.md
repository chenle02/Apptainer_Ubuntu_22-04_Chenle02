# Apptainer -- Ubuntu_22-04 by Chenle02
## How to use 
1. Build the image
```
sudo apptainer build Apptainder_Ubuntu_22-04_Chenle02.sif Apptainder_Ubuntu_22-04_Chenle02.def
```

2. Build the sandbox
```
apptainer build sandbox Apptainder_Ubuntu_22-04_Chenle02.sif ~/Apptainer_Ubutntu_22-04_Chenel02
```

3. Use it
```
apptainer shell --writeable ~/Apptainder_Ubuntu_22-04_Chenle02
```
