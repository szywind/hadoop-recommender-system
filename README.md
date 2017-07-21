# A recommender system built on hadoop 2.x

Refer to [this repo](https://github.com/bsspirit/maven_hadoop_template) and make it work on hadoop 2.x.
This distributed recommender system is based on itemCF algorithm, which is implemented by several map-reduce steps.

Run on hadoop:
```shell
hadoop jar myHadoop.jar org.conan.myhadoop.recommend.Recommend
```

Check the results:
```shell
hdfs dfs -cat /user/hdfs/recommend/step6/part-r-00000
```

