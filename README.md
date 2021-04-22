# numpywren

- install pywren: ```pip install pywren```
- run ```pywren-setup```
- update ```.numpywren_config``` and ```.pywren_config``` in experiments folder
- run ```python setup.py install```
- run ```python setup.py build```
- run ```python experiments/cholesky_experiment.py 100```

Changes compared to original version:
- Removed ```control_plane``` and ```redis``` and switched to only use s3 buckets

Current problem:
- call result on pywren futures crashes - line 173 in binops.py
