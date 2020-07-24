#  各种数据类型
## 数据类型
- 整型
    - unsigned类型：unsigned short,unsigned long 
    - int ,long long,
- 浮点型
    - double
    - float
## 字符类型
- UTF-8: `char a = 'M';`
- Unicode: `wchar_t a = L'Z'; `
## 字符串
- 字符数组：`char a[]="This is a paragraph.";`
## 逻辑类型
- `bool a =true;`
## Size_t类型
- 计算某种类型byte数：`size_t s = sizeof( int );`
## 枚举类型
- 构建枚举类：
(```) enum class Race{
    Dannel,
    Teklan,
    Ivyn,
    Moiran,
    Julian,
    Aidan
};
(```)
- 引用枚举类：`Race a = Race :: Dannel`;
## 联合类型
- 构建联合类型
(```)
union Movie {
    char name[12];
    int year;
    char author[10];
    bool show;
};
(```)
- 引用联合类型：`Movie Harry_Poter;Harry_Poter.year = 2012;`
## 自定义类型
- struct类型（POD）；构建跟引用与Union相同
- struct方法：在类内定义函数，变量在类内全部可见。
- struct容器：调用自身名字函数，设置默认值
