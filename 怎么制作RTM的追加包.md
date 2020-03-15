# 怎么制作RTM的追加包

-----------------

###### ~~教不会算我输~~

# 目录
## 1.创建追加包(基础)[P1][P1]
> ### 1.1zip结构图[p1.1][##### __P1.1__文件目录]
> > #### __P1.1.1__图片示例[p1.1.1][##### __P1.1.1__图片示例]
> ### __P1.2__支持格式[p1.2][##### __P1.2__支持格式]
> > #### __P1.2.1__介绍[p1.2.1][##### __P1.2.1__备注]
> > #### __P1.2.1__图片示例[p1.2.2][##### __P1.2.2__图片示例]
>
> ### __P1.3__图片纹理[p1.3][##### __P1.3__图片纹理]
> ### __P1.4__声音追加[p1.4][##### __P1.4__声音追加]
## 2.模型[P2][P2]











##### __P1.1__文件目录

```mermaid
graph TD
1[追加包的名字 #不要中文# ] 
      1 -->2.1[LICENCE.txt]
      1 -->3.1[README.txt]
      1 -->1.2[assets]
    1.2 -->1.3[name]
    1.2 -->1.4[minecraft]
    1.3 -->1.5[sounds]
    1.5 -->1.6[name.ogg]
    1.4 -->1.4.1[models]
    1.4 -->1.4.2[scripts]
    1.4 -->1.4.3[textures]
    1.4.1 -->1.4.1.1[json]
    1.4.3 -->1.4.3.1[rrs]
    1.4.3 -->1.4.3.2[sighboard]
    1.4.3 -->1.4.3.3[train]
    Z[流程图]
```

##### __P1.1.1__图片示例
![img1](J:\md\rtm append\rtm-append-learn\img1.png)

# ------------------------------------------------------------------------

![img2](J:\md\rtm append\rtm-append-learn\img2.png)

---
---------------
---
##### __P1.2__支持格式

```mermaid
graph TD
1[类型]
1-->2[3D建模]
1-->3[贴图]
1-->4[音效]
1-->5[JavaScript]

2-->2.1[.mqo]
2-->2.2[.obj]
2-->2.3[.mat  __材质__]

3-->3.1[.png]

4-->4.1[.ogg  __只能__]

5-->5.1[.js]
```
# ------------------------------------------------------------------------
##### __P1.2.1__备注

```mermaid
graph LR
0[类型]
0-->2[.mqo]
0-->3[.obj]
0-->4[.mat]

2-->2.1[水杉 #metasequoia 专用格式]
3-->3.1[Blender和metsaequoia等大多数建模软件可用]
4-->4.1[obj自带的贴图文件]

1[3D]
```
---
---------------
---
```mermaid
graph LR
0[类型]
0-->2[.ngto]
0-->3[.ngtz]

2-->2.1[在 MCTC 中 #我制作的Mod# 导出文件]
3-->3.1[将多个NGTO进行了ZIP压缩,改后缀]

1[3D特殊]
```
---
---------------
---
```mermaid
graph LR
0[类型]
0-->2[.png]

2-->2.1[自带alpha通道的图片]

1[贴图]
```

---
---------------
---
```mermaid
graph LR
0[类型]
0-->2[.ogg]

2-->2.1[音效格式]

1[音效]
```

---
---------------
---
```mermaid
graph LR
0[类型]
0-->2[.js]

2-->2.1[游戏里控制车门开关]

1[音效]
```
# ------------------------------------------------------------------------
##### __P1.2.2__图片示例
![img3](J:\md\rtm append\rtm-append-learn\img3.png)

# ------------------------------------------------------------------------
##### __P1.3__图片纹理
	可参考assets/miecraft/textures/tarin/(# 不固定)/button_neme.png
	       外框=256px × 256px   按钮=160 × 32
![img](J:\md\rtm append\rtm-append-learn\img4.png)

                                      操作和创建步骤如下 

​                                                                                   软件AI 2018 CC pro

​                                                                           有不明白的加QQ群387092893

​                                                                                        新建button_test 

<img src="J:\md\rtm append\rtm-append-learn\img5.png" alt="img" style="zoom:150%;" />

​                                                                       使用矩形工具在AI里创建106 × 32的灰色 

<img src="J:\md\rtm append\rtm-append-learn\img6.png" alt="img" style="zoom:150%;" />
![img](J:\md\rtm append\rtm-append-learn\img7.png)

​                                                                                      加上亿点细节——成果
![img](J:\md\rtm append\rtm-append-learn\img8.png)

##  导出

![img](J:\md\rtm append\rtm-append-learn\img9.png)
# 画质高可能会导致游戏崩溃
<img src="J:\md\rtm append\rtm-append-learn\button_test.png" alt="img" style="zoom:200%;" />

##### __P1.4__声音追加

#                                   **to be continued**  