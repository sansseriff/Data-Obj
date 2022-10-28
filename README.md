# Data_Obj

A custom class for making data objects that are easily exported/imported as json. Uses orjson for fast export and 
import of numpy arrays. 

The export and import methods can handle DataObj objects inside other DataObj objects. 

## Why not just use the python pickle library? 
--> Answer: Json is a more universal format than python pickle. The exports from this library could be parsed by Matlab, 
Javascript, etc. The use of orjson here should also make this much faster than python pickle for large datasets. 



# Usage

install orjson and/or numpy:
```shell
pip install numpy
pip install orjson
```

or with anaconda:

```shell
conda install numpy
conda install -c conda-forge orjson
```