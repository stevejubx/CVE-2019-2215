# CVE-2019-2215
Android Kernel Vulnerability (CVE-2019-2215) temporary root PoC.

It works on Google [Pixel 2](https://dl.google.com/dl/android/aosp/walleye-ota-qp1a.190711.020-d326cba7.zip)/[Pixel 2 XL](https://dl.google.com/dl/android/aosp/taimen-ota-qp1a.190711.020-4757f073.zip) (walleye/taimen) devices running the September 2019 QP1A.190711.020 image with kernel version-BuildID **`4.4.177-g83bee1dc48e8`**.

<p align=center>
  <img src="images/preview.png"/>
</p>

#### Usage
Now, Binary support arm64 only.


```console

$ git clone https://github.com/jsirichai/CVE-2019-2215.git
$ cd CVE-2019-2215
$ adb push bin/cve-2019-2215 /data/local/tmp
$ adb shell
$ chmod +x /data/local/tmp/cve-2019-2215
$ ./data/local/tmp/cve-2019-2215
```

## Credits
https://github.com/kangtastic/cve-2019-2215
