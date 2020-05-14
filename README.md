# Chinese_phonemes
中文汉语的音素

THCHS_30 数据 下载地址 ： http://www.openslr.org/resources/18/data_thchs30.tgz    

aishell   数据 下载地址 ： http://www.openslr.org/resources/33/data_aishell.tgz     

ST-CMDS-20170001_1-OS    数据 下载地址 ： http://www.openslr.org/resources/38/ST-CMDS-20170001_1-OS.tar.gz     

标贝 数据下载地址: https://weixinxcxdb.oss-cn-beijing.aliyuncs.com/gwYinPinKu/BZNSYP.rar   


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

 aishell_1_yin_s:  

{'BAC009S0002W0122': 'ee er2 d uei4 l ou2 sh i4 ch eng2 j iao1 ii i4 zh i4 z uo4 ii iong4 z uei4 d a4 d e x ian4 g ou4 ',  
 'BAC009S0002W0123': 'ii ie3 ch eng2 uu uei2 d i4 f ang1 zh eng4 f u3 d e ii ian3 zh ong1 d ing1 ',  
 'BAC009S0002W0124': 'z i4 l iou4 vv ve4 d i3 h u1 h e2 h ao4 t e4 sh i4 sh uai4 x ian1 x van1 b u4 q v3 x iao1 x ian4 g ou4 h ou4 ',   
 'BAC009S0002W0125': 'g e4 d i4 zh eng4 f u3 b ian4 f en1 f en1 g en1 j in4 ',   
 'BAC009S0002W0126': 'j in3 ii i2 g e4 d uo1 vv ve4 d e sh i2 j ian1 l i3 ',   
 'BAC009S0002W0127': 'ch u2 l e b ei3 j ing1 sh ang4 h ai3 g uang3 zh ou1 sh en1 zh en4 s i4 g e4 ii i1 x ian4 ch eng2 sh i4 h e2 s an1 ii ia4 zh i1 uu uai4 ',   
......  
 'BAC009S0002W0146': 'ii iou3 ii ie4 n ei4 r en2 sh i4 d ang1 sh i2 j iou4 zh i3 ch u1 ',   
 'BAC009S0002W0147': 'd uei4 vv v2 f ang2 d i4 ch an3 ii ie4 d e ii ing3 x iang3 l ai2 sh uo1 ',     
 'BAC009S0002W0148': 'h uo4 b i4 sh ou3 d uan4 l i4 l ai2 sh i4 c i4 j i1 sh i4 ch ang3 x v1 q iou2 d e z uei4 ii iou3 x iao4 g ong1 j v4 ',   
 'BAC009S0002W0149': 'c i3 c i4 j iang4 x i1 j iang1 ch eng2 uu uei2 sh i4 ch ang3 j ia1 k uai4 k u4 c uen2 q v4 h ua4 d e zh ong4 ii iao4 l i4 q i4 '}     



























