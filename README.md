# dual-fisheye-video-stitching-in-Python3

The repository forked from : https://github.com/cynricfu/dual-fisheye-video-stitching

and I translate it from Python2 to Python3, in addition to this I modified some bugs which can not run in Python3.

## Dependencies

* Python 3.7
* OpenCV 3.4.4

## Run

```
python main.py [-h] [-o OUTPUT.XYZ] INPUT.XYZ
```

```
positional arguments:
  INPUT.XYZ             path to the input dual fisheye video

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT.XYZ, --output OUTPUT.XYZ
                        path to the output equirectangular video
```

## Data Download

You can download some original video data from : https://github.com/cynricfu/dual-fisheye-video-stitching/tree/master/data