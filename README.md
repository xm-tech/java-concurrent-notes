>锁类型:

* 内置锁(`synchronized`)

* 可重入锁(`ReentrantLock`)

```  java

public class Hello {
	public static void main(String[] args) {
		System.out.println("hello");
	}
}
```

|java|c|golang|
|:---|:---:|---:|
|jvm <mark>[^1]</mark>|pointer|coroutine|

[^1]: hotspot, openjdk