### Scanner 类 reader 对象
我们在使用 Java 写代码时，如果想要实现输入操作怎么办呢，这时候我们需要用到的是 Scanner 类来实现获取用户从键盘上的输入操作。

Scanner 类是一个基于正则表达式的文本扫描器，它可以从文件、输入流、字符串中解析出基本类型值和字符串值；Scanner 类可以任意地对字符串和基本类型(如 int 和 double )的数据进行分析。

当我们引入 Scanner 这个类的时候，我们需要导入java.util.Scanner这个类。

`

import java.util.Scanner;

public class Demo {

    public static void main(String[] args) {
    
    // 创建一个Scanner的实例对象，这个对象可以为用户提供输入，将这个实例对象命名为reader，后面我们可以直接用reader调用Scanner类的相关方法
    
    Scanner reader = new Scanner(System.in);
    
    // 从键盘处接收用户输入的浮点型数据
    
     double a = reader.nextDouble();
     
     System.out.print("输入的数据为：" + a);
     
    }
    
}
`
