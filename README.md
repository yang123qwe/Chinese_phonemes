# Chinese_phonemes
中文汉语的音素

THCHS_30 数据 下载地址 ： http://www.openslr.org/resources/18/data_thchs30.tgz    

aishell   数据 下载地址 ： http://www.openslr.org/resources/33/data_aishell.tgz     

ST-CMDS-20170001_1-OS    数据 下载地址 ： http://www.openslr.org/resources/38/ST-CMDS-20170001_1-OS.tar.gz   

eg：   

import numpy as np  
aishell_1_sou = np.load('data/aishell_1_sou.npy').item()  
aishell_1_yin_s = np.load('data/aishell_1_yin_s.npy').item()  



aishell_1_sou :  
{'BAC009S0002W0122': '而对楼市成交抑制作用最大的限购',  
 'BAC009S0002W0123': '也成为地方政府的眼中钉',   
 'BAC009S0002W0124': '自六月底呼和浩特市率先宣布取消限购后',   
 'BAC009S0002W0125': '各地政府便纷纷跟进',   
 'BAC009S0002W0126': '仅一个多月的时间里',   
 'BAC009S0002W0127': '除了北京上海广州深圳四个一线城市和三亚之外',   
 'BAC009S0002W0128': '四十六个限购城市当中',   
 'BAC009S0002W0129': '四十一个已正式取消或变相,   
 ......   
  'BAC009S0002W0144': '刺激改善型需求入市',   
 'BAC009S0002W0145': '而另外一剂楼市强心剂则当属央行的不对称降息',  
 'BAC009S0002W0146': '有业内人士当时就指出',
 'BAC009S0002W0147': '对于房地产业的影响来说'}
 
