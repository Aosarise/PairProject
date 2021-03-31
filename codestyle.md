代码规范
缩进
嵌套关系使用四个space键进行缩进，取代tab键;

函数名
使用lowerCamelCase风格，必须遵从驼峰形式；正确英文拼写和语法，易于理解；不使用＄符号和——作为开头；

每行最多字符数
每行最多100，超过部份需要换行；

函数最大行数
简单函数在20行内结束，复杂函数在100行内结束

类命名
使用UpperCamelCase风格，必须遵从驼峰形式；正确英文拼写和语法，易于理解；不使用＄符号和——作为开头；

常量
只使用大写字母，尽量简洁明了，多个单词之间用下划线隔开；

空行规则
类定义语句、变量定义语句、方法定义语句、常量定义语句之间分块空行隔开；不同业务逻辑或者语义之间空一行；

注释规则
对整个方法或者类注释于类名或方法名的{后；对某句的注释直接跟在单句后面；单个文件结束后注释于底部；

操作符前后空格
双目操作符前后各加一个空格；

测试代码块
public class User{

public static final double PI = 3.14;//这是一个常量

static int test1 = 1;//这是一个变量
static double test2 = 2;//这是另一个变量

public int getValue（）{//这是一个函数
    return value;
}

private int chooseValue（）{//这是另一个函数
    if （value == 0）
    return 1；
    else
    return 0；
}

}
/*这是文末注释*/