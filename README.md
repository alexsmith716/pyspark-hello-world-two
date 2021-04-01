# pyspark-hello-world-two


### Command:

`% spark-submit pyspark-hello-world-two.py`


### Output:

`21/04/01 16:29:29 INFO TaskSchedulerImpl: Killing all running tasks in stage 1: Stage finished`

`
 --> 114
a --> 4
= --> 4
frequency --> 4
the --> 4
words --> 3
word --> 3
counts --> 3
import --> 2
#Get --> 2
lines --> 2
each --> 2
and --> 2
to --> 2
for --> 2
in --> 2
operator --> 1
pyspark --> 1
def --> 1
main(): --> 1
'''Program --> 1
entry --> 1
point''' --> 1
#Intialize --> 1
spark --> 1
context --> 1
with --> 1
pyspark.SparkContext("local", --> 1
"PySparkWordCount") --> 1
as --> 1
sc: --> 1
RDD --> 1
containing --> 1
from --> 1
this --> 1
script --> 1
file --> 1
sc.textFile(__file__) --> 1
#Split --> 1
line --> 1
into --> 1
assign --> 1
of --> 1
1 --> 1
lines.flatMap(lambda --> 1
line: --> 1
line.split(" --> 1
")).map(lambda --> 1
word: --> 1
(word, --> 1
1)) --> 1
#count --> 1
words.reduceByKey(operator.add) --> 1
#Sort --> 1
descending --> 1
order --> 1
based --> 1
on --> 1
sorted_counts --> 1
counts.sortBy(lambda --> 1
x: --> 1
x[1], --> 1
False) --> 1
an --> 1
iterator --> 1
over --> 1
print --> 1
its --> 1
word,count --> 1
sorted_counts.toLocalIterator(): --> 1
print(u"{} --> 1
--> --> 1
{}".format(word, --> 1
count)) --> 1
if --> 1
__name__ --> 1
== --> 1
"__main__": --> 1
main() --> 1
`
