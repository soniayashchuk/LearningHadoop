# LearningHadoop

Companion Repository to *Learning Hadoop* course on Linked In Learning

Assuming that:

```/wordcount/input``` - input directory in HDFS ```/wordcount/output``` - output directory in HDFS Sample text-files as input:

Run the application:
```
bin/hadoop jar wc.jar WordCount /wordcount/input /wordcount/output

bin/hadoop fs -cat /wordcount/output/part-r-00000 Bye 1 Goodbye 1 Hadoop 2 Hello 2 World 2
```
