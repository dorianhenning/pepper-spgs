# Guide to Setting Up and Installing Required Software for the Pepper Robot

## Setting Up the Conda envirionment

```
conda create --name spgs python=2.7

pip install numpy ipython
pip install qi
```

## Download SDKs

https://www.aldebaran.com/en/support/pepper-naoqi-2-9/downloads-softwares

extract...

move to software

add to path:

```
NAOQI_PATH="{$HOME}/software/pynaoqi-python2.7-2.5.7.1-linux64"

export PYTHONPATH=${PYTHONPATH}:${NAOQI_PATH}/lib/python2.7/site-packages
export QI_SDK_PREFIX=${NAOQI_PATH}
```


