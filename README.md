# Parallel neural network training
Utilizing multithreaded performace capabilities to decrease the training time of 
a neural network using OpenMP

# mnist-from-scratch
Code for training basic neural networks, especially the MNIST numbers dataset.

### Get the training dataset
```
kaggle datasets download -d oddrationale/mnist-in-csv
unzip mnist-in-csv.zip -d data
```

### Assemble and start the project
```
make
```

# If you want to measure time
```
time ./main
```

But don't forget to reassemble the project before that
```
make clean
make
```

### Video
[![Watch the video](https://img.youtube.com/vi/ReOxVMxS83o/maxresdefault.jpg)](https://youtu.be/ReOxVMxS83o)
