# 联系方式

我叫小飞,我的爱好是

- 唱歌
- 羽毛球
- 游泳

我喜欢的书有

1. 三国演义
2. 水浒传
3. 西游记

我学过的编程语言有 `JAVA` `HTML` `JavaScript` 

下面是一个单例模式

```java
public class World {
    private static final World SINGLETON_INSTANCE = new World();

    public static World getInstance() {
        return SINGLETON_INSTANCE;
    }

    private World() {

    }
}
```
