#  **Psi-k tutorial workshop : [ML-IP 2021](https://www.mlip-workshop-2021.xyz)**

**Day :** Wednesday 17th November (2021)

**Title :** From Atomistic to Coarse Grained: Active Learning Strategies for Gaussian Approximation Potential

### Installation 

```
conda env create --file  env.yml  -p /your/path

cp -r AL4GAP  /your/path/conda_psik/lib/python3.7/site-packages/

conda activate /your/path

```

### How to run ?

```
cd Notebook/

unzip traj.extxyz.zip

conda activate /your/path

export PYTHONPATH=/your/path/conda_psik/lib/python3.7/site-packages/

jupyter-notebook tutorial_AL4GAP.ipynb

```



## Acknowledgements
This material is based upon work supported by Laboratory Directed Research and Development (LDRD) funding from Argonne National Laboratory, provided by the Director, Office of Science, of the U.S. Department of Energy under Contract No. DE-AC02-06CH11357. This research used resources of the Argonne Leadership Computing Facility, which is a DOE Office of Science User Facility sup-ported under Contract DE-AC02-06CH11357. Argonne National Laboratory's work was supported by the U.S. Department of Energy, Office of Science, under contract DE-AC02-06CH11357. We gratefully acknowledge the computing resources provided on Bebop; a high-performance computing cluster operated by the Laboratory Computing Resource Center at Argonne National Laboratory. This research used resources of the Advanced Photon Source, a U.S. Department of Energy (DOE) Office of Science User Facility operated for the DOE Office of Science by Argonne National Laboratory under Contract No. DE-AC02-06CH11357. Use of the Center for Nanoscale Materials, an Office of Science user facility, was supported by the U.S. Department of Energy, Office of Science, Office of Basic Energy Sciences, under Contract No. DE-AC02-06CH11357.
