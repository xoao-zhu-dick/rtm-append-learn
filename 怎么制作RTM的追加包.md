# 怎么制作RTM的追加包

-----------------


## beta版0.4.1（bug上天，QQ群：287092893）

###### ~~教不会算我输~~

# 目录

## 0.准备应用
> #### 模型
> >metasequoia4[下载在QQ群]
> >
> >3Dmax [敬请期待][]
> >
> >MCTE  [敬请期待][]
> #### 材质
> >AI    32x[下载][http://prdl-download.adobe.com/Illustrator/C1208DBFE1D04A81A21C62CDF6A96AC6/1509976186706/AdobeIllustrator22_HD_win32.zip?red=a]     64x[下载][http://prdl-download.adobe.com/Illustrator/C1208DBFE1D04A81A21C62CDF6A96AC6/1509968804429/AdobeIllustrator22_HD_win64.zip?red=a]
> >
> >PS   32x[下载][http://prdl-download.adobe.com/Photoshop/66A1D1E00DE44601B041A631261EC584/1507845150875/AdobePhotoshop19-mul.zip?red=a]     64x[下载][http://prdl-download.adobe.com/Photoshop/66A1D1E00DE44601B041A631261EC584/1507846032938/AdobePhotoshop19-mul_x64.zip?red=a]
> >
> >画图
> #### 音效
> #### 编辑
> > DW  32x[下载][http://prdl-download.adobe.com/Dreamweaver/0D145873957D4FEF849999B43723DA1E/1509108370613/Dreamweaver%20CC%202018%20Set-up.exe?red=a]  64x[下载][http://prdl-download.adobe.com/Dreamweaver/0D145873957D4FEF849999B43723DA1E/1509107886842/Dreamweaver%20CC%202018%20Set-up.exe?red=a]
> >
> > 记事本
> #### 其他
> adobe 18 pro注册机[下载][http://xzc.198424.com/amtemupainter.zip]

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
> >####  __P1.6__声音js[p1.6.1][# __使用此功能时，不需要“sound Stop”到“sound D S”的行驶声音项目__]
> >####  __P1.6__贴图js[p1.6.2][## (3)贴图脚本]
>
> ### __T1_追加表[t1][##### __T1__可追加表格]
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


# 画质高可能会导致游戏崩溃

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

* 参数“su”是负责语音控制的项目。使用其中的各种方法。suplay Sound也可以用于改变已经播放的声音的音量和间距。

* ### 可使用的类参考
名前固定|value值|介绍|备注
:----:|:----:|:----:|:----:
getSpeed()|float|获取当前速度|
inTunnel()|boolean|是否在隧道里|
playSound(# String domain, String path, float volume, float pitch, boolean repeat)|void|播放声音|
stopSound(# String domain, String path)|void|声音停止
stopAllSounds()|void|停止所有声音|
getData(int id)|Object|获得Data|
setData(Object value)|void |设置Data|
getMaxSpeed()|float |获取最高时速|列车专用
getNotch()|int |获取当前档位|列车专用
getState()|byte |获取最高时速|列车专用
isComplessorActive()|booleam |列车制动风|列车专用

># value值的含义
># 数据类型包括基本类型和构造类型；基本数据类型又包括整形、实型、浮点型(float)、布尔型(boolean)、字符型；构造类型又包括数组类型、类、接口（多重继承）
>
>> ## float:是原始数据类型，赋值方法float b = 111.111f; //数字后面的f代表float类型，否则会报错。而Float，是对float的封装，是一个类，所以赋值时需要赋给一个对象
```js
{
  float a = 666.888
}
```

> > ##  boolean:boolean是java中的布尔型（逻辑型）数据类型，在java中boolean值只能是true和false，而不能用0和1代替，并且一定要小写。
> > >### 使用关键词 new 来定义 Boolean 对象。下面的代码定义了一个名为 myBoolean 的逻辑对象：
```js
{
  var myBoolean = new Boolean()
}
```

> > >### 下面的所有的代码行均会创建初始值为 false 的 Boolean 对象：
```js
{
  var myBoolean = new Boolean(0 null "" NaN)
}
```

> > >### 下面的所有的代码行均会创初始值为 true 的 Boolean 对象：
```js
{
  var myBoolean = new Boolean(1 true "true" "falae" "Bill Gates")
}
```

> > ##  void:它代表的意思是什么也不返回，我们在开发过程中经常会用到，如一个方法不需要返回值时可以使用void关键字，在main方法中也是void关键字:
```js
{
  public static void getName() {
        String name = "username";
        System.out.println(name);
}
```

> > ## object:这种参数定义是在不确定方法参数的情况下的一种多态表现形式。即这个方法可以传递多个参数，这个参数的个数是不确定的。这样你在方法体中需要相应的做些处理。因为Object是基类，所以使用Object
```js
{
  public class Example{

   Public void f(Object obj){
   }
}
```

> > ## byte:通常在读取非文本文件时（如图片，声音，可执行文件）需要用字节数组来保存文件的内容，在下载文件时，也是用byte数组作临时的缓冲器接收文件内容。所以说byte在文件操作时是必不可少的。不管是对文件写入还是读取都要用到。
```js
{
 public class A {
 public static void main(String[] args) {
  int b = 456;
  byte test = (byte) b;
  System.out.println(test);
 }
}
```

> > ## int: int表示的就是定义整型数据 
```js
{
  public void demo(int[] n){}
}
```

## (3)贴图脚本
### （3.1）可根据绘图脚本部件详细控制绘图。但是需要OPEN GL的知识。特别是坐标处理很特殊，请注意。

```js
var renderClass = 'jp.ngt.rtm.render.MachinePartsRenderer'; ···后面讲
importPackage(Packages.org.lwjgl.opengl); ···准备使用GL 11类
importPackage(Packages.jp.ngt.rtm.render); ···准备使用Parts类
importPackage(Packages.jp.ngt.ngtlib.math); ···使用NGTMATH等级的准备（任意）

var turnR; ···全局变量

function init(par1, par2) ···初期化处理（後述、必須）
{
   main = renderer.registerParts(new Parts('pole', 'light_a', 'light_b', 'body1', 'body2', 'body3', 'dirB', 'body4', 'base', 'dirR', 'dirL'));···创建部件，并列出用于该部件的对象名称

   lightL = renderer.registerParts(new Parts('light_L', 'dirR'));
   lightR = renderer.registerParts(new Parts('light_R', 'dirL'));
   bar = renderer.registerParts(new Parts('bar0', 'bar1'));
   turnR = (renderer.getModelName().equals("CrossingGate01R")); ···变量初始化，这里准备了根据模型名称分开处理的变量
   
   }
   
   function render(entity, pass, par3) ···贴图处理（後述、必須）
   {
   GL11.glPushMatrix(); ···保存当前坐标状态(glPopmatrix（）和组合使用)
   
   var light = renderer.getLightState(entity);
   
   if(pass == RenderPass.NORMAL.id) ···绘制常规部件
   {
     main.render(renderer); ···绘制部件
     
     GL11.glPushMatrix();
     var move = renderer.getMovingCount(entity) * (turnR ? 90.0 : - 90.0);
     renderer.rotate(move, 'Z', 0.0, 0.5337, -0.24); ···Z轴旋转
     bar.render(renderer);
     GL11.glPopMatrix();
     
     switch(light)
     {
     case 0: lightL.render(renderer);break;
     case 1: lightR.render(renderer);break;
    }
  }
  else if(pass == RenderPass.LIGHT.id) ···绘制发光部件
  {
  switch(light)
  {
  case 0: lightR.render(renderer);break;
  case 1: lightL.render(renderer);break;
    }
  }
     GL11.glPopMatrix(); ···调用以glPushmatrix（）保存的坐标状态
 }
```
创建部件，并列出用于该部件的对象名称

![img17](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img17.png)

绘制发光部件

![img18](https://github.com/xoao-zhu-dick/rtm-append-learn/blob/master/img18.png)





---
---------------
---



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
