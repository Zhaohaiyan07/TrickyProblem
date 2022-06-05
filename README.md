# TrickyProblem
Jot down some tricky(only for me) problem and thoughts
1. 将markdown文件上传到Github上，有些语法无法识别：
  - ①加粗的`**`后如果没有空格就会失效；
  - 公式的部分前后也得有空格，且在APP（iOS）上无论如何调整都无法显示公式块
  - typora中的下标是用`~`来将要下标的内容囊括起来，而github-flavored的是用`<sub></sub>`，在github上直接修改文件，好像无法查找替换，只能在本地修改，虽然用了正则表达式快速找到了目标，但是不知道替换的时候如何利用正则表达式将`Q~t~`替换成`Q<sub>t</sub>`，好像在vsc的搜索框无法实现，得自己写一个程序
3. 
