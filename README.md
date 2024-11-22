# Geko

> Geko 是一个基于 Python 制作的解释型语言, 与一名小学生制作

## 📦安装与使用

### 安装

[下载 Geko 最新版本](https://github.com/HelloEasytong/Geko/releases)
或者
[获取 Geko 源码](https://github.com/HelloEasytong/Geko/releases)

### 使用

#### 获取 Geko 源码
##### 下载所需库
```pip install -r requirements.txt```

> 然后，运行```main.py```,输入你要执行的 Geko 文件 或 输入 ```<您的 Python 解释器的路径> <main.py 的路径> --cr <你要执行的 Geko 文件>``` 即可

#### 下载 Geko 最新版本

> 运行```geko.exe```,输入你要执行的 Geko 文件 或 输入 ```geko --cr <你要执行的 Geko 文件>``` 即可
>> 注： 第二种方法需要先将 Geko 添加到环境变量中

## ✅联系方式
![qq](https://img.shields.io/badge/QQ-3661724417_Easytong-aqua)

![bilibili](https://img.shields.io/badge/Bilibili-3546576561637431_Easytong-red)

![email](https://img.shields.io/badge/Email-helloeasytong%40outlook.com-blue)

![github](https://img.shields.io/badge/GitHub-HelloEasytong-green?logo=github)

## 🔖大致思路
> 1. 读取文件
> 2. 使用正则表达式进行匹配
> 3. 生成抽象语法树，定义一个变量用来确定当前位置，定义一个函数用来检测代码是否正确，定义一个函数用来解析表达式
> 4. 根据抽象语法树逐步运行

## 📝待办事项

- 异常处理
- 优化代码速度
- 数组与字典
- 读取文件
- 优化代码可读性
- 优化代码可维护性
- 一系列BUG
- 常用函数
- if-elif-else结构

## 🕓 版本
* 最新版本：1.0.20250106
* 发布日期：2025年1月6日

## 💖语法
- ```text <cell>``` 打印 \<cell>
- ```read -> <class>```  将用户输入的值转换为\<class> 类型返回
- ```<var_name> = <text>``` 将 \<text> 赋值给 \<var_name>
- ```until <condiction> {<cell>}``` 执行 \<cell> 直到 \<condiction> 为真
- ```repeat <condiction> {<cell>}``` 重复执行 \<condiction> 次 \<cell>
- ```using <module> -> <name>``` 导入 \<module> 并将其命名为 \<name>

> ```->``` 及之后的指令可省略

> 这里只介绍部分命令，其他命令可参照发布视频

