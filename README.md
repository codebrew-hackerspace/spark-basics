# spark-basics


Spark is an execution framework taht will distributed your data across a culster and process the data in parallel. 

### Spark vs MapReduce

* MapReduce is a framework that shuffles things in and out of disk, wich inserts barriers between stages to read and write. Spark maintains the data in memory, which allows it to use magnitides faster. 
* Spark uses lazy evaulation in which it will record the actions required, but not actually start the computation till the result is requested. 