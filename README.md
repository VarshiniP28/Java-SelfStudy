# Java-SelfStudy
Team members - Varshini P(1RV18IS058),Soundarya R(1RV18IS051) and Sinchana R(1RV18IS049)

A simple neural network that recognise handwritten characters

The neural network is written in C++. Instead, the GUI and the application of the neural network is written in Java (that involves loading MNINST images, scaling and converting them to an usable format and so on...) . C++ neural network functionalities are accessed from Java through JNI. 

Training/Test data to be used can be found here: http://yann.lecun.com/exdb/mnist/

## How to build the application

You can build the application by using gradle. Java JDK min 1.8 is necessary to build this project.
Open the terminal and move to the root of this project then execute
```
gradlew assemble
```

Build files will be generated into a folder named ```build```. The executable ```.jar``` will be generated into ```build/libs```.


