# JavaScript-demo-2
JS的语法

### 表达式和语句
表达式：表达式是有值的，如1+1
语句：是一段可执行的代码，不总是有值

### 标识符的规则
标识符的第一个字符只能是Unicode字母、$、_ 和中文。
后面的字符随意

### if ... else
if (表达式) {
  语句1
} else {
  语句2
}
一般不建议省略{}

### 循环语句
while(表达式) {
  循环体
}

do {
  循环体
}while(表达式)

for(语句1; 表达式; 语句3) {
  循环体
}

### break和continue
与上面的循环语句一起用
break跳出整个循环，continue跳过本次循环继续下一次循环

### label
label :
   statement
   
label为不属于任何关键字的JavaScript标识符
statement为JavaScript语句
