# SpecialistSystemHomework
# 专家系统的作业

## 一、井字棋
本程序使用alpha-beta算法解决井字棋人机对弈的问题，运行环境要求是jdk1.8。
初始化时，玩家需要选择棋子种类，输入1代表选择X，输入2代表选择O，输入其他的属于错误输入，默认选O。
初始时玩家需要选择先手还是后手，输入1表示选择先手，输入2表示选择后手，输入其他为错误操作，默认是先手。
棋盘为3*3大小，分别用1-9表示，按1-9在对应的位置下棋。输入1-9以外的按键或者在有棋子的地方输入属于非法操作，系统会要求重新输入。

## 二、推导系统
本程序实现了一个简单的正向推导系统，运行环境要求为jdk1.8
本程序的规则存放在rules.txt文件中，要求文件的编码为utf-8格式，并且使用相对路径访问，文件必须与项目在同一路径下。
本程序输入中文即可推导出结果，结果的准确程度取决于输入事实的完善程度。
输入1表示逻辑推导，输入已有事实，事实要求只有特征即可，例如“是XX”或者“有XX”或者“吃肉”“会飞”之类的，即可得到结果。输入2表示添加规则，一次只能添加一条规则，先输入前件，后输入后件，同样输入只能输入特征和结论，即“是XX”，“有XX”。输入3表示删除规则，系统会把所有规则罗列出来，选择要删除的规则，一次删除一条。输入4表示退出系统。

## 三、决策树
本系统实现了决策树生成，只要输入合适的数据集，系统就可以生成一棵决策树。
数据集的输入使用二维数组，输入的个数为：序号+特征+分类结果。同时要把特征名以及对应的特征值传给程序，如此一来系统就可以建决策树。



### 环境说明
Windows/Java

### Copyright and License
SpecialistSystemHomework is provided under the [Apache-2.0 license](https://github.com/baidu/AnyQ/blob/master/LICENSE).
