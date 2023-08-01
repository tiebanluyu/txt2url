
# 这个软件十分简易，但功能及其强大
# 功能
## 获取了url的结尾#后面的内容
## 将其以代码形式执行
# 兼容性
## 因为这个软件直接将那些内容传到底层，不用识别了再执行对应的代码
## 所以，兼容性极高
## 要是执行不了，肯定是你的浏览器太弱了
# 安全性
1. ## 如果你是网页的编写人员，那么 _相当安全_
## ＃号后面的不会被传到服务器，你看到的内容完全在你自己的电脑上，泄密不可能发生在这个环节
2. ## 如果你是网页的浏览者，那么 _存在一定风险_
## 服务器无法决定你看到什么，因为服务器压根不知道
## 网页的安全性和可信度完全取决于提供者
## 啊对，可以执行恶意代码
# 所以咋么用
## 编写者将html代码加在网址https://tiebanluyu.github.io/txt2url/main.html#后
## 注意有一个#号
## 举例 

## https://tiebanluyu.github.io/txt2url/main.html#<h1>1</h1><p>test/</p>

## 但直接这样打支持性一般，连markdown都会出问题
## 所以还提供了其他形式
## 在main.html后再加上mode=h（html）
## 就支持html代码（默认）
## mode=b（base64）
## 可以传入base64编码之后的结果
## mode=t（test）
## 可以输入文本（不是md），用“\n”表示换行
## 可以这样
## https://tiebanluyu.github.io/txt2url/main.html?mode=t#hello\nworld
## https://tiebanluyu.github.io/txt2url/main.html?mode=b#5ZCD5LqG5ZCX

## 由于js对中文不太友好，所以不对中文是否会乱码作任何保证
## 但经过测试，问题不大
