# Answering-BillionScale-LabelConstrained-Reachability-Queries-within-Microsecond
The small label version
In the previous runtime experiments in this paper and this code, we follow the settings of LI+ (code:https://github.com/DeLaChance/LCR/tree/master/LCRIndexing/experiments/Index/UnboundedLCR, paper:Landmark Indexing for Evaluation of Label-Constrained Reachability Queries). In this setting, every query would run 5 times and then get the average time. However, the CPU cache may speedup these queries. Thus, we recommond to test all the queries together and then produce the runtime performance if anyone investigates this topic further.


Our code: https://drive.google.com/file/d/1u4rw4052cXUM4t8Wva24DUSnz6k_XD9K/view
