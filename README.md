# TIoU-metric on Python3

The project is forked from https://github.com/Yuliang-Liu/TIoU-metric. The original project only works on Python2. I modify some codes and run the project on Python3.

# Get started

Install prerequisite packages:
```shell
pip install shapely Polygon3
```

Test on IC15:
```shell
python ic15/script.py -g=gt.zip -s=pixellinkch4.zip
```

Test on CTW1500:
```shell
python curved-tiou/script.py -g=ctw1500-gt.zip -s=det_ctw1500.zip
```

Test on Total-Text:
```shell
python curved-tiou/script.py -g=total-text-gt.zip -s=total-text_baseline.zip
```

