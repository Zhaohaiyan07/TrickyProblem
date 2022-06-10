# TrickyProblem
Jot down some tricky(only for me) problem and thoughts
1. 将markdown文件上传到Github上，有些语法无法识别：
  - 加粗的`**`后如果没有空格就会失效；时而生效，时而失效：
    - ![加粗](https://user-images.githubusercontent.com/44341897/173023629-92ae3305-7889-411b-9c08-5213c42d547f.PNG)
    - ![加粗生效](https://user-images.githubusercontent.com/44341897/173023677-ae4c79c2-4098-4de8-8754-55900386c30d.PNG)
    - ![加粗奇怪](https://user-images.githubusercontent.com/44341897/173023693-2445a448-ba0d-4711-a288-26afe4f8259a.PNG)
  - 公式的部分前后也得有空格，且在APP（iOS）上无论如何调整都无法显示公式块
  - typora中的下标是用`~`来将要下标的内容囊括起来，而github-flavored的是用`<sub></sub>`，在github上直接修改文件，好像无法查找替换，只能在本地修改，虽然用了正则表达式快速找到了目标，但是不知道替换的时候如何利用正则表达式将`Q~t~`替换成`Q<sub>t</sub>`，好像在vsc的搜索框无法实现，得自己写一个程序
    - ![typora subscript](https://user-images.githubusercontent.com/44341897/173023172-0fe16ff4-b632-43ed-973b-3021c6c08a36.PNG)
    - ![github subscript](https://user-images.githubusercontent.com/44341897/173023236-a2937e2a-8c6e-4b0a-8670-f57430f82858.PNG)
  - 在github上`~`是删除号：
    - ![删除号](https://user-images.githubusercontent.com/44341897/173023106-d93c91bc-69cc-4d53-9ea7-f084c51b5726.PNG)
    - ![删除号2](https://user-images.githubusercontent.com/44341897/173023157-a6c49205-ea6b-4357-9df8-223f97b89f1e.PNG)

3. 
