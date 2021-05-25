## Steps

### cmake

```
mkdir -p build && cd build && cmake ..
cmake -S . -B build
cmake . -Bbuild
```

### make

```
make -C build
```

## run

```
./build/yolo img/1.jpg
```

## refs

1. [详细记录u版YOLOv5目标检测ncnn实现 - 知乎](https://zhuanlan.zhihu.com/p/275989233)
2. [权重下载链接](https://github.com/nihui/ncnn-assets/tree/master/models)
3. [c++ - How to make cmake output to the "build" directory? - Stack Overflow](https://stackoverflow.com/questions/52022717/how-to-make-cmake-output-to-the-build-directory)
