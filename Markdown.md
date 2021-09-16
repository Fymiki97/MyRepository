# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
</br></br>
## 使用\`,\`凸显关键字
正文内容，一段技术的描述以及基本概述信息</br>这是新的一行，
一些细节的描述,包含：`架构分析`,`细节设计`
## 使用\*编写无序列表
* 负载均衡
	* 子级内容A
		* 子级内容B三级内容
* 分布式及横向扩展
* 高可用HA数据库
* 长连接有效认证

## 使用\*内容\*修饰为斜体
*斜体数据*

## 使用\*\*内容\*\*修饰为粗体
**粗体数据**

## Tree效果
> Tree_01
>> Tree_02
>>> Tree_03


## 有序列表
1. 第一层
	1. 第一层
	2. 第二层
		1. 第一层
2. 第二层

##分割线

可用使用`-`或者`*`创建分割线</br>

 - - - -  - - 
* * * * * * *
## 使用\`\`\`语言 代码内容\`\`\` 格式加入代码块
```c
	#include <stdio.h>
	#include <stdlib.h>
	#include <string.h>
	//这是一段c代码
```
```cpp
	#include <iostream>
	using namespace std;
	/*这是一段C++代码 */
```

```python
	import 库名
	#使用一段Python代码
```

```bash
	sudo apt-get install git #安装git命令
```
- - - - - - - - - -
## \`\`\`flow 流程内容\`\`\`，绘制流程图
```flow
st=>start: 开始
e=>end: 登录
io1=>inputoutput: 输入用户名密码
sub1=>subroutine: 数据库查询子类
cond=>condition: 是否有此用户
cond2=>condition: 密码是否正确
op=>operation: 读入用户信息

st->io1->sub1->cond
cond(yes,right)->cond2
cond(no)->io1(right)
cond2(yes,right)->op->e
cond2(no)->io1
```
