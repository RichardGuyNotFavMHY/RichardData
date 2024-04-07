# RichardData 
里茶馆，今天我就来给你表演大记忆恢复术.jpg
## 一个自动化记录里茶馆内所有发帖&回帖的项目
## 重要信息
**更新**：本项目依然在平稳运行(2024/4/8)。由于存在盒信息的缘故，目前本项目的数据库暂不支持全样分享，但是依然接受查询请求。    
**如果您需要有图片版本的备份，请直接在该项目内发issues**  
### 这是什么？这个项目怎么来的？(高可读)
这是一个自动记录里茶馆内所有发帖、回帖数据的项目。该项目的数据来源于一些自动化的魔法，关注结果即可。
### 这个项目是如何组织文件的？我该如何使用这个项目？
### 如何组织文件
本项目有用的东西是一个文件(index.csv)和一个压缩文件。  
其中index.csv文件存放的是本项目记录到的数据的索引。  
Data文件放的就是每个帖子自动记录到的数据，每一个文件就代表了一篇帖子，打开文件就能查看帖子的内容。
### 如何使用本项目的数据
0. 请准备一个**markdown阅读器**(推荐Firefox浏览器+md浏览插件)。
1. 请完全下载本项目的index.csv与Data.7z文件。(Data.7z文件请从MEGA网盘下载)
2. 这个项目很简单，其中index.csv是本项目的索引，在其中您能查看到本项目记录的所有主题。
3. 当您确认您要查询的主题后,请使用window的资源管理器的搜索功能，搜索该主题的名称，定位到文件。
4. 随后打开该文件，用markdown阅读器打开它，查阅帖子。

### 有没有集成一点的解决方案(文本搜索工具)  
有的，您可以使用Textseek、Recoll、FileLocator Pro等集成文字搜索软件。  
在使用集成文字搜索软件时，您一般只需要配置软件的搜索目录，然后开启搜索，就能正常使用了。  
![图片](https://github.com/RichardGuyNotFavMHY/RichardData/assets/140698973/b8356594-378f-4b60-b24f-894af912bf08)


### 如果我不确定我要查询的帖子的标题或者tid该怎么办？
#### aka如何进行模糊搜索
答案是利用window的powershell脚本，通过powershell可以完成关键字筛选、上下文披露、按时间按关键词按发帖id查询等高级操作。  
千万不要认为这总方法很复杂，大多数情况下您只需要询问bing、gpt等聊天机器人，描述请您的需求，它们就会帮你编写好脚本。
  
**如果您系统的powershell在处理中文编码时遇到困难，您可以尝试使用python来作为您的筛选助手，两者效果相同**  
**如果您使用集成搜索工具，则进行此类搜索也将变得较为容易**  

### Linux、macOS、Android等平台怎么办？
Go help yourself.jpg 核心是查看csv文件，搜索文件夹内文件的名称，以及一个markdown文件查看器。

### 本项目是超人吗？有什么局限性？
本项目不是超人，有其局限性。
1. 本项目只能记录通过审核的发帖、回帖，对于没有通过审核的内容无能为力。
2. 对于变更频繁的(例如刚发出来版务就锁了的)帖子，如果变化快于本项目的自动扫描时间，本项目也无能为力。

### 友情项目
[玩原神玩的，米游瓜事件存档](https://github.com/riccaxricca/wyswd)  
[世界树.属于米哈游玩家的百科(事件记录、玩家讨论、发声)](http://hoyo.life/)

### 未来企划
1. 本项目仅仅做了数据记录，缺乏针对事件事发地相关帖子的摘要。希望未来有高人参与项目，做好特定帖子的简介，给后人留好路牌。
