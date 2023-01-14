# Dataset Description
The dataset contains a manipulation of users' search logs data collected during a search experimentation.

The format of each file is as follows:

## <topic>/doc-gain.csv
document ID, document knwoledge gain,url

## <topic>/query-click.csv
user ID, query ID, query term, query time, click time, rank of the clicked page in SERP, page URL, page title, page description,active time

## <topic>/testscore.csv
user ID, pre-test score, post-test score, knowlegde gain

## <topic>/user-cumgain.csv
user ID, the cumulative knowledge gain brought until the i-th interaction sequence

## <topic>/user-docbehaviour.csv
user ID, document visited on the xth interaction sequence

## <topic>/user-docgain.csv
user ID, knowledge gain brought by the document read at the i-th interaction sequence. The first column 0 is for the model intercept.

## <topic>/user-querybehaviour.csv
user ID, query submitted on the xth interaction sequence

## <topic>/Information_need.txt
the need presented to users before initiating their search task.

##Avggain_perseq.csv
topic, average gain per sequence. The first column is for the model intercept.

##querydoc_index.csv
query term, url ID

##tasks_and_testq.tsv
Test Question, Answer