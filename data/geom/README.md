# How to build GEOM-DRUGS

1. Download the file at https://dataverse.harvard.edu/file.xhtml?fileId=4360331&version=2.0   (Warning: 50gb):
     `wget https://dataverse.harvard.edu/api/access/datafile/4360331`
   
2. Untar it and move it to `data/geom/`, then `tar -xzvf 4360331`
3. Make sure `msgpack` is installed: `conda install -c conda-forge msgpack-python`
4. `python3 build_geom_dataset.py`