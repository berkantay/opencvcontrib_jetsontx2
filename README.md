OpenCV and OpenCV contrib package installation for NVIDIA Jetson products.

**Usage**

If you are building for python2.7 

``` do nothing with python link```


For python3.6 or newer 

``` 
cd /usr/bin
sudo rm python #need privileges
sudo ln -s python python3.6
```

We did that because makefile looks for the default python and it should see the python3 or newer version for build.