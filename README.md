# Deep Neural Network Test Coverage: How Far Are We?

#### Environment configuration
The version of related libraries are in the `requirements.txt`.

You can install related libraries with the following command：
```shell
pip install -r requirements.txt
```

#### Running
Please use the following command to obtain the results of structural coverage (except Driving and Speech-Commands):
```shell
python get_nc.py -d mnist -num_classes 10 -target cw
```

Please use the following command to obtain the results of structural coverage of the Driving:
```shell
python get_nc_driving.py -target light
```

Please use the following command to obtain the results of structural coverage of the Speech-Commands:
```shell
python get_nc_speech.py
```

Please use the following command to obtain the results of non-structural coverage:
```shell
python general_main.py -d mnist -target cw
```

#### Results
Also, we put the raw data results for all experiments in `results_nc` and `results_sc`.


