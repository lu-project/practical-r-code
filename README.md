# Practical R Codes
There are two code files in this respository for different purposes. The details of each line of code are in the code comments. 
 
* ```rxGlm-benchmark.R ``` will run a number of intensive, parallel linear algebra computations to show the performance gains that are possible through the use of Microsoft R Server and CRAN.  With simulated data, the benchmarks specifically compare matrix calculations on one thread versus multi-threads. 
* ```LinearPlotSample.R ```  will generate synthetic data that will be used to generate the data for Microsoft R Server API testing purpose. Idea is to generate small and simple enough data where it is possible to easily analyze without complex methods. The data that will generate is based on the simplest mathematical function f(x) = (noise) y where noise is random number between -1 and 1.


