# cscope 生成索引文件的方法

两个步骤：

* `find `pwd` -name "*.[ch]" -o -name "*.cpp" > cscope.files`
* `cscope -Rbq`