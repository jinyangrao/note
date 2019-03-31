# 1. 标题
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题

# 2.字体
*斜体*  
**加粗**  
***斜体加粗***  
~~删除的文字~~  

# 3.引用
>引用的文字1
>>引用的文字嵌套2
>>>引用的文字嵌套3
>>>>引用的文字4
>>>引用的文字5
>>>>>引用的文字6

>ddd
asdas
asdas
asdasd

>ddd

>dd
>dd
>dd
>dd

# 4.分割线
--- 
----
***
****

# 5.图片  
 ![picture](markdown_picture.png "title")  

 # 6.超链接
 [百度](http://baidu.com)  
 [简书](http://jianshu.com)

 # 7.1列表
 - 列表
 - 列表
 + 列表
 + 列表
 * 列表
 * 列表

# 7.2有序列表
1. 有序列表
2. 有序列表
3. 有序列表
5. 有序列表

# 7.3列表嵌套
- 一级无须列表
   - 二级无序列表
      - 三级无序列表
         - 四级无序列表
- 以及无序列表

- 一级无序列表
   1. 二级有序列表
   2. 二级有序列表
   4. 二级有序列表

1. 一级有序列表
   - 二级无序李彪
   - 二级无序列表
   + 二级无序列表

1. 一级有序列表
   1. 二级有序列表
   1. 二级有序列表

# 8.表格
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

# 9.代码
`单行代码`  
```
public class Demo() {
    public static void main(String[] args) {
    }
}
```

# 10.流程图 vscode不支持
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```