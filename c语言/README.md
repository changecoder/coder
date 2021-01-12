# C语言

## 程序结构
```
#include <stdio.h>
 
int main()
{
   /* My first C program */
   printf("Hello, World! \n");
   
   return 0;
}
```
1. "#include <stdio.h>"为预处理器指令，告诉编译器实际处理之前要先包含stdio.h文件
2. "int main()" 主函数，程序从此处开始
3. "/* */" 注释
4. “printf” 函数，打印出文本内容
5. “return 0" 终止函数，并返回0

## 基本语法

### 标识符
标识符是用来标识变量、函数，或任何其他用户自定义项目的名称。 
一个标识符以字母 A-Z 或 a-z 或下划线 _ 开始，后跟零个或多个字母、下划线和数字（0-9）。 
C 标识符内不允许出现标点字符

## 数据类型

### 基本类型

#### 整数类型
1. char 
2. unsigned 
3. signed char 
4. int
5. unsigned int 
6. short 
7. unsigned short 
8. long 
9. unsigned long
各种类型的存储大小与系统位数有关，但目前通用的以64位系统为主。 
表达式 sizeof(type) 得到对象或类型的存储字节大小。
#### 浮点类型
1. float
2. double
3. long double
### void类型
类型说明符 void 表明没有可用的值。
1. 函数返回为空
2. 函数参数为空
3. 指针指向 void
### 枚举类型
被用来定义在程序中只能赋予其一定的离散整数值的变量。
### 派生类型
它们包括：指针类型、数组类型、结构类型、共用体类型和函数类型。