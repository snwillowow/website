# <font face="仿宋" color=orange>Markdown入门教程</font>
## <center><font face="楷体" size=5>willow</font></center>

### 一、 准备工作
（先下载插件：
    markdown all in one
    markdown preview enhanced
    paste image
 使用右键，点击open preview to the side (或者ctrl+k后再输入v)
 ）

### 二、 基本语法
1. **标题**
#一级标题
##二级标题
###三级标题
####四级标题
#####五级标题
######六级标题
2. **引用**
>听我说谢谢你
>>不用谢
3. **列表**
   1. 无序列表
   + 列表
   - 列表
   * 列表
   2. 有序列表
   3. 嵌套
   4. todoList
        - [x] a
        - [ ] b
        - [ ] c
4. **表格**
    | 左对齐 | 居中对齐 | 右对齐 |
    | :----- | :------: | -----: |
    | a      |    b     |      c |
5. **段落**
- 换行——两个以上的空格再回车  
- 分割线三个***
  ***
- 字体
    |     字体      |      代码      | 快捷键 |
    | :-----------: | :------------: | :----: |
    |    *斜体*     |      * *       | ctrl+i |
    |   ==高亮==    |     == ==      |
    |   **粗体**    |     ** **      | ctrl+B |
    | ***粗斜体***  |    *** ***     |
    |   ~~删除~~    |     ~~ ~~      |
    | <u>下划线</u> | ```<u> </u>``` |
  - 脚注
  - 请查看上标[^1]。
6. **代码**
   ```
   #include <stdio.h>
   int main(){
    printf("hello world");
    return 0;
   }
   ```
`print("hello world");`
7. **超链接**
  -[github]:https://github.com
  - 登录github[点击链接][指针]
  - 登录也可以[点击链接](https://github.com)
8. **图片**
  - [使用图床](https://imgchr.com/)
  - [查看图片](微信图片_20260925235301_19099_895-1.jpg)
  - 插入图片
  ![插入图片](微信图片_20260925235301_19099_895.jpg)
### 三、其他操作
  -**插入latex公式**
     - 行内显示公式: $f(x)=a+b$
 - 块内显示数学公式:
$$
\begin{Bmatrix}
  a&b\\
  c&d
  \end{Bmatrix}
$$
### 四、 导出为pdf文档
  - Open in Browser-手动另存PDF文档

[^1]:开心！

[指针]:https://github.com

