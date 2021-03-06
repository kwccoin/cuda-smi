cuda-smi
====

On Windows/Linux, there is a program called `nvidia-smi` for checking the memory and general statistics of GPUs.

There is no such thing on MacOS.

This program tries to bring that ability to MacOS. However at the current version, it can only check the free memory and some basic info.

Usage
====

Run
```sh
./compile.sh
```

The output file is `cuda-smi`. Feel free to copy it to somewhere in your `PATH` directories.

When you run `cuda-smi`, it will give something like this:

```sh
$ cuda-smi
Device 0 [PCIe 0:1:0.0]: GeForce GT 750M (CC 3.0): 1584.6 of 2047.6 MB (i.e. 77.4%) Free
```

Your mileage may vary.

Credits
====
I made this code based on [al42and's project](https://github.com/al42and/cuda-smi).
