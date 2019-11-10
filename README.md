Anamoly_detection
The data set contains labelled logs from a production Hadoop Distributed File System (HDFS) cluster. The logs contain both anomalous as well as normal events. We need to build a system that can accurately detect anomalies in HDFS logs.

Original source: http://iiis.tsinghua.edu.cn/~weixu/sospdata.html

sorted.log:      Raw log (sorted by time stamp)
col_header.txt:  Which log message each column represents
rawTFVector.txt: Message count matrix
mlabel.txt:      Labels faults ("1") or no-faults ("0") in first column; each
                 line corresponds to a line in rawTFVector.txt

