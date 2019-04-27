# CppProjectX
This is a project designed for composing music with your numbered music notation.

Project Name:  
i MusicNote  
## How This Works？
This is a program mainly programmed in C++ and using Qt 5 as UI.  
## What Can I do on this application?
You can input your simplified Music notation according to the international standard of music notation.  
Click "Play" ,and the rest is for us.  
Click [Here](#001) to a Chinese Version.  



### 项目名称： {#001} 
i悦谱。  
### 项目简介：

> "输入简谱，轻点Play，剩下的交给我们。"

本项目是为了服务手边没有乐器或者不会演奏乐器的人，您需要的只是一段乐谱和一个带有音响的一台计算机，只要输入您想输入的任意乐谱，运行该程序，即可用计算机来演奏这段美妙动听的旋律。  
乐谱包含以01234567为基本四分音符，每个音符用英文逗号分开，如：1,2,3,4等，0代表休止符。在音符前输入：“+-#!” 加号表示此音升高八度，减号则降八度，井号升半音，叹号降半音。用户也可以自己谱曲，并使用内置支持的乐器进行调试曲目的操作。  

项目实现过程：
1、音频截取，储存为若干元音：乐器初定为钢琴、吉他、口琴，输入乐谱。  
2、音频调试测试音准，统一音频格式以便于合成处理。  
3、项目界面设计：    
请查看[项目简介.doc]文件  
4、乐谱输入部分的分析：输入部分的乐谱通过字符串进行处理，通过对输入乐谱的处理，定向到文件提取指定的单元音频，再按照设定的每分钟拍数进行播放，可以满足部分用户倍速播放的需求。  
  
人员分工：  
A（发起者）:  
协调整体工作，处理并测试音频与源代码，设计美化项目界面。    
B：主要负责收集音频制作元音，初步估计有60个元音文件需要处理测试，工作量较大。  
C、D、E：主要负责，在B收集的时间根据预先设定好的文件格式处理输入乐谱数据并模拟提取相应的音频文件，协助B完成音频收集测试。在收集完毕之后调试播放曲目，设计美化项目图形界面。  
