# 怎么制作RTM的追加包

-----------------
## beta版0.3（bug，QQ群：287092893）
###### ~~教不会算我输~~

# 目录

## 0.准备应用
>模型
>>metasequoia4[下载在QQ群]
>>3Dmax [敬请期待][]
>>MCTE  [敬请期待][]
>材质
>>AI 32x[下载][http://prdl-download.adobe.com/Illustrator/C1208DBFE1D04A81A21C62CDF6A96AC6/1509976186706/AdobeIllustrator22_HD_win32.zip?red=a] 64x[下载][http://prdl-download.adobe.com/Illustrator/C1208DBFE1D04A81A21C62CDF6A96AC6/1509968804429/AdobeIllustrator22_HD_win64.zip?red=a]
>>PS 32x[下载][http://prdl-download.adobe.com/Photoshop/66A1D1E00DE44601B041A631261EC584/1507845150875/AdobePhotoshop19-mul.zip?red=a] 64x[下载][http://prdl-download.adobe.com/Photoshop/66A1D1E00DE44601B041A631261EC584/1507846032938/AdobePhotoshop19-mul_x64.zip?red=a]
>>画图
>音效
>编辑
>>DW  32x[下载][http://prdl-download.adobe.com/Dreamweaver/0D145873957D4FEF849999B43723DA1E/1509108370613/Dreamweaver%20CC%202018%20Set-up.exe?red=a] 64x[下载][http://prdl-download.adobe.com/Dreamweaver/0D145873957D4FEF849999B43723DA1E/1509107886842/Dreamweaver%20CC%202018%20Set-up.exe?red=a]
>>记事本
>其他
>>adobe 18 pro注册机[下载][http://xzc.198424.com/amtemupainter.zip]

## 1.创建追加包(基础)[P1][P1]
> ### 1.1zip结构图[p1.1][##### __P1.1__文件目录]
> > #### __P1.1.1__图片示例[p1.1.1][##### __P1.1.1__图片示例]
> ### __P1.2__支持格式[p1.2][##### __P1.2__支持格式]
> > #### __P1.2.1__介绍[p1.2.1][##### __P1.2.1__备注]
> > #### __P1.2.1__图片示例[p1.2.2][##### __P1.2.2__图片示例]
> ### __P1.3__图片纹理(显示)[p1.3][##### __P1.3__图片纹理]
> ### __P1.4__声音追加[p1.4][##### __P1.4__声音追加]
> ### __P1.5__json的写法[p1.5][##### __P1.5__json的写法]
> >### __P1.5.1__普通[p1.5.1][# 普通举例]
> >### __P1.5.2__通用[p1.5.2][# 通用举例]
> ### __P1.6__js脚本[p1.6][#### __P1.6__js脚本]
>  ### __T1_追加表[t1][##### __T1__可追加表格]
## 2.模型[P2][P2]











##### __P1.1__文件目录

![img1](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/f1.png)

##### __P1.1.1__图片示例

![img1](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img1.png)

# ------------------------------------------------------------------------

![img2](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img2.png)


# ------------------------------------------------------------------------

![img2](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img3.png)





---
---------------
---
##### __P1.2__支持格式

![img2](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/f2.png)

# ------------------------------------------------------------------------
##### __P1.2.1__备注

![img2](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/f3.png)

---
---------------
---
![img2](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/f4.png)

---
---------------
---
![img2](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/f5.png)

---
---------------
---
![img2](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/f6.png)

---
---------------
---
![img2](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/f7.png)

# ------------------------------------------------------------------------
##### __P1.2.2__图片示例

![img3](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img3.png)


# ------------------------------------------------------------------------
##### __P1.3__图片纹理
	可参考assets/miecraft/textures/tarin/(# 不固定)/button_neme.png
	       外框=256px × 256px   按钮=160 × 32


![img](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img4.png)


                                      操作和创建步骤如下 

#                                                                    软件AI 2018 CC pro

#                                                                 有不明白的加QQ群387092893

#                                                                         新建button_test 


<img src="https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img5.png" alt="img" style="zoom:150%;">

#                                                             使用矩形工具在AI里创建106 × 32的灰色 



![img6](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img6.png)

![img7](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img7.png)


#                                                                         加上亿点细节——成果
![img8](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img8.png)

##  导出

![img9](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img9.png)

# 画质高可能会导致游戏崩溃


##### __P1.4__声音追加
#### 文件路径展示 `name.zip/assets/name/sounds/name.ogg`
#### 文件指定展示 (js)`name:sounds/name.ogg`

---
---------------
---

## 图片示例
![img11](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img12.png)

![img12](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img11.png)
## json详见[]
---
---------------
---


##### __P1.5__json的写法
# 简介
## JSON（Javascript Object Notation）是轻量的数据记述语言之一。语法以Javascript为基础，但并非Javascript.专用的数据形式，而是为了在各种软件和编程语言之间传递数据而设计的。（来自维基百科）

## 在RTM中，对于几乎所有的模型，为了让模型作者能够细致地改变设定，将JSON作为设定文件使用。文字编码是Unicode。基本上使用UTF-8。Windows的记事本等默认为Shift-JIS，保存时需要更改。

![img14](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img14.png)

# 普通举例
```json
{
"name1":10····整数
"name2":0.5····数值（浮点数）
"name3":abc···文字
"name4":true····真假值
"name5":[0,1,2]····匹配UV
"name6":{····编辑对象
  "nemaname":"aaa"
    }

}
```

## 图片示例
![img15](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img15.png)

# 注意事项

### 更改颜色的方式
## 虽然有在车辆和招牌上指定颜色的项目，但在JSON中通常不能使用彩色编码中使用的十六进制标记。因此，用JSON指定颜色时需要转换成十进制数。转换时请使用函数计算器等。（Windows的话是标准的)
## 举例 网页---8进制:FF0000（红色）--------16711680

# 通用举例
### 所有机型通用项目以下为除招牌、标识外所有种类的通用项目（已知为切踏）。
```json
{
   "useCustomColor":false ··· 是否允许更改游戏中的颜色
   "tags":"name" ···模型选择画面中的搜索关键字（空格分隔符)
   "defaultData":"scale=(double)1.0,type=(string)Normal", ···设置DataMap
   "scale":1.0 ···NGTO模型专用
   "offset":[0.0,0.0,0.0] ···模型绘制位置（从Enity中心的相对坐标)
   "smoothing":true, ···平滑
   "doCulling":true, ··· 单面表示（mqo和obj）
   "accuracy":"low" ··· 注释(5.1)
   "serverScriptPath":"scripts/server/ShieldMachine.js" ···服务器脚本路径
   "guiSriptPath":"Sript/gui/RenderGuiFighther.js  ··· GUI脚本路径
   "guiTexture":"textures/gui/fighter_hud.png", ··· 交通工具GUI的自定义纹理
   "renderAABB":[-0.5,0.0,-0.5,0.5,1.0,0.5] ··· 有无绘制判断用Box的大小
}
```
(5.1)可通过accuracy“设置点坐标的精度。

LOW|MEDIUM
:----:|:----:
有6.000的范围。如果是在这个范围内且不是很细的模型的话，选择这个可以减少内存使用量|通常

# ※JSON的项目可部分省略省略省略时，RTM侧将设置默认值。（绘图脚本和坐标精度等）如果不列出不可省略的项目，则会崩溃。

## 图片示例

![img16](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img16.png)

---
---------------
---

#### __P1.6__js脚本

# 注意事项
>## (1)规范脚本
>>###   在RTM中可以定制声音播放和模型绘制，通过脚本保留处理。形式是Javascript（以下简称JS）。关于JS的语法，这里不太详细说明。
>>###   关于可使用的方法，仅主要记载在这里。如果是RTM和NGTLIB的类public的方法全部可以调用，想详细知道的话请看附带的源代码。
>## (2)音效脚本
>>### 使用脚本而不使用默认的声音设置的话，可以通过速度和陷波来调整声音、音节、音量等，进行细致的控制。

# __使用此功能时，不需要“sound Stop”到“sound D S”的行驶声音项目__

```js
function onUpdate(su){ ···每一tick调用方法
   var speed = su.getSpeed();···获取现在的速度
   var maxSp = 120;
   var notch = su.getNotch();···获取现在的挡位
   
   if(notch == 0){
       su.stopSound('rtm', 'train.223_s0'); ··· 停止指定的声音，参数（・有域sound.json的文件夹），・声音名称）
       su.stopSound('rtm', 'train.223_s1');
       su.stopSound('rtm', 'train.223_s2');
   }else{
       if(speed > 0.0){
           su.stopSound('rtm', 'train.223_air');
           
           if(speed < 20.0){
                var vol = 1.0;
                if(speed < 5.0){
                    vol = speed / 5.0;
                }else if(speed > 10.0){
                   vol = (20.0 - speed) / 10.0;
                }
                su.playSound('rtm', 'train.223_s0', vol, 1.0);
            }else{
                su.stopSound('rtm', 'train.223_s0');
            }
            
            var pitch = 1.0;
            
            if(speed >= 8.0){
                 var vol = 1.0;
                 if(speed < 12.0){
                     vol = (speed - 8.0) / 4.0;
                     su.playSound('rtm', 'train.223_s1', vol, pitch);
             }else{
                su.stopSound('rtm', 'train.223_s1');
             }
             
             var inTunnel = su.inTunnel();
             if(speed >= 12.0){
                 pitch = (speed - 12.0) / (maxSp - 12.0) + 0.9;
                 su.playSound('rtm', 'train.223_s2', 2.0, pitch);
                 
                 var vol = (speed - 12.0) / (maxSp - 12.0);
                 if(inTunnel){
                      su.stopSound('rtm', 'train.223_run');
                      su.playSound('rtm', 'train.223_run_tunnel', vol, 1.0);
                 }else{
                     su.stopSound('rtm', 'train.223_run_tunnel');
                     su.playSound('rtm', 'train.223_run', vol, 1.0);
                   }
                 }else{
                     su.stopSound('rtm', 'train.223_s2');
                     su.stopSound('rtm', 'train.223_run_tunnel');
                     su.stopSound('rtm', 'train.223_run');
                  }
                 }else{
                    su.stopSound('rtm', 'train.223_s0');
                    su.playSound('rtm', 'train.223_air', 1.0, 1.0);
                }
           }
       }
```

---
---------------
---

##### __T1__可追加表格

类型|主体|后缀|备注
:----:|:----:|:----:|:----:
-|物|品|-
`枪械`|ModelFirearm_|-|无
`铁轨`|ModelRail_|-|无
`信号机`|ModelSignal_|-|无
`集装箱`|ModelContainer_|-|无
`NPC`|ModelNPC_|-|无
`线`|ModelWier_|-|无
`看板`|SignBoard_|-|无
`标记`|RRS_|-|不用json
`信号（中转）`|ModelConnector_|Relay|无
`信号（输入）`|ModelConnector_|Input|无
`信号（输出）`|ModelConnector_|Output|无
`道闸（切踏）`|ModelMachine_|Gate|无
`重点` #（未知）|ModelMachine_|Point|无
`道闸（乘车）` |ModelMachine_|Turnstile|无
`买票机`|ModelMachine_|Vendor|无
`照明（标记）` |ModelMachine_|Light|无
`驻车器`|ModelMachine_|BumpingPost|无
`ATC`|ModelMachine_|Antenna_Send|无
`列车检测器`|ModelMachine_|Antenna_Receive|无
`照明`|ModelOrnament_|Lamp|无
`楼梯（斜）`|ModelOrnament_|Stair|无
`楼梯（平）`|ModelOrnament_|Scaffold|无
`架线柱`|ModelOrnament_|Pole|无
`管道`|ModelOrnament_|Pipe|无
`植物`|ModelOrnament_|Plant|无
轨|道|机|车
`电力机车`|ModelTrain_|EC|无
`动力机车`|ModelTrain_|DC|无
`货物车`|ModelTrain_|CC|无
`坦克（火炮车）`|ModelTrain_|TC|无
`测试车`|ModelTrain_|Test|无
-|载|具|-
`轿车`|ModelVehicle_|Car|无
`飞机`|ModelTrain_|Plane|无
`船`|ModelTrain_|Ship|无

源素材
![img13](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img13.png)

---
---------------
---





#                                   **to be continued**  