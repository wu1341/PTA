# PTA
诗歌文本分析器。本人的第一个仓库，程序很烂，请大佬们多多包容。

共有两种版本：普通版、AI版。

# 普通版

普通版文件中包含 普通版.py、1.jpg

运行版本：Python 3.8.3

•	GUI 框架：tkinter

•	分词工具：jieba

•	可视化：matplotlib、wordcloud

•	机器学习：sklearn（TF-IDF、LDA）

•	图像处理：Pillow

•	数据处理：re、collections、numpy

使用说明：
      
1. txt.文件请使用utf-8编码；
2. 请将 普通版.py、1.jpg 放在同一文件夹内。
3. 按下“开始分析”后，点击“文本分析”与“词云”查看分析结果


 图片版权说明：      
  <img width="600" height="944" alt="1" src="https://github.com/user-attachments/assets/7c3e3b50-d577-48fa-87b1-859551b3ea30" />
       
1.jpg（上图）为B站vup云崎早_haya的十万粉纪念回免费壁纸的其中一张，已获得云崎早_haya的口头许可。

云崎早_haya是B站最有文化的vup之一，擅长背文言文、诗歌，与本程序目的：诗歌文本分析相符合，故使用其图片。

云崎早_haya的B站主页：https://space.bilibili.com/3493074573461871

# AI版

AI版文件中包含 AI版.py、2.jpg

运行版本：Python 3.8.3

库文件：requests、Pillow（PIL)

使用说明：

 1. txt.文件请使用utf-8编码；
 2. 本人使用LM Stuidio进行本地AI部署，使用时请注意修改API和key；
 3. 本程序限定AI的最大输出token数为8192，若token超过8192，则AI停止输出；（本人使用 qwen-3.5-9b Q6量化 测验时未超过8192tokens)
 4. 请将 AI版.py、2.jpg 放在同一文件夹内。

图片版权说明：
  <img width="1537" height="768" alt="2" src="https://github.com/user-attachments/assets/bcf59f00-05a1-40dc-98d6-7d2845575a48" />    
        
2.jpg（上图）为B站vup云崎早_haya的免费动态壁纸的其中一帧，已获得云崎早_haya的口头许可。

云崎早_haya是B站最有文化的vup之一，擅长背文言文、诗歌，与本程序目的：诗歌文本分析相符合，故使用其图片。

云崎早_haya的B站主页：https://space.bilibili.com/3493074573461871
