For testing on your own machine, you need to install the following libraries.

Steps to reproduce the results
- git clone https://github.com/ahmedshabib/cs7641-assignment2
- cd cs7641-assignment2
- git clone https://github.com/pushkar/ABAGAIL
- cd AGAGAIL
- ant
- cd ..
- cp AGAGAIL/AGAGAIL.jar .
- java -cp AGAGAIL.jar  phishing_rhc.java
- java -cp AGAGAIL.jar phishing_sa_val.java
- java -cp AGAGAIL.jar phishing_ga_val.java
- java -cp AGAGAIL.jar phishingwebsite_finaltest.java

## For Part 2
### 1. Traveling Salesman Problem - Highlights GA
- java -cp ABAGAIL.jar opt.test.TravelingSalesman_Toy
### 2. Continuous Peaks Problem - Highlights SA
- java -cp ABAGAIL.jar opt.test.ContinuousPeaks_Toy
### 3. Four Peaks Problem - Highlights MIMIC
- java -cp ABAGAIL.jar opt.test.TravelingSalesman_Toy

The model results (training times and fitness function values) are stored in .csv files located at ~\ABAGAIL\Optimization_Results

Code modified from
https://github.com/kylewest520/CS-7641---Machine-Learning/tree/master/Assignment%202%20Randomized%20Optimization
