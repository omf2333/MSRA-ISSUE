## issue#309

>Level6_TuneParams_MultiProcess.py ：<https://github.com/omf2333/MSRA-ISSUE/blob/master/Level6_TuneParams_MultiProcess.py>

第9.7节中的网格搜索，原代码中使用单进程方式一个个计算参数组合，比较慢。这里提供了一个python的多进程代码来并发地进行三组参数的计算，提高效率。

## issue#315

>Level6_TuneParams_RandomSearch.py ：<https://github.com/omf2333/MSRA-ISSUE/blob/master/Level6_TuneParams_RandomSearch.py>

这里实现了第9.7.4中的随机搜索算法，其中`batch_size` 和`learning rate`和`hidden unit`都是在对数尺度上的均匀分布进行采样。

