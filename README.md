抖音快手爆料大全网站抖音热门真空集锦合集

3.2 Collection 接口详解

Collection接口是 Java 集合框架中所有单列集合的根接口，它定义了一系列操作集合的方法，这些方法是所有单列集合都必须实现的。可以把Collection接口想象成一个模板，它规定了集合应该具备的基本功能。
常用方法

    添加元素：
        boolean add(E e)：向集合中添加一个元素，如果添加成功则返回true，否则返回false。比如：

Collection<String> collection = new ArrayList<>();
boolean added = collection.add("apple");
System.out.println(added);  // 输出 true

typescript
运行

    1
    2
    3

    boolean addAll(Collection<? extends E> c)：将指定集合中的所有元素添加到当前集合中，如果当前集合因为这个操作而发生了改变，则返回true。例如：
————————————————
