### 1111-IR-hw3
data file: https://drive.google.com/file/d/1JQ3iVLRvR4OJasantsz2UBXT2WXaW3Ft/view?usp=sharing

# test hadoop
```
   hadoop fs -put speech speech
   hadoop jar hadoop-examples-1.2.1.jar wordcount speech result
   hadoop fs -cat result/part-r-00000
```
```
   hadoop jar output.jar Max Ep.txt result_max
   hadoop fs -cat result_max/part-r-00000
```
