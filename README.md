# 这是一个一级标题

## 这是一个二级标题

#### 这是一个四级标题

~~这是一个五级标题~~

**这是一个加粗字体**

*这是一个斜体字*

```java
//这是一段JAVA代码
public static boolean isINTC(String s) { // 数字常量自动机
		if (s.charAt(0) == '0') {
			if (s.length() == 1) {
				return true;
			} else {
				return false;
			}
		}
		if (!Data.D1.contains(s.charAt(0))) {
			return false;
		}
		for (int i=1; i < s.length(); i++) {
			if (!Data.D.contains(s.charAt(i))) {
				return false;
			}
		}
		return true;
	}
```

1. 这是编号列表
2. 这是第二行
3. 这是第三行

- 这是符号列表
- 无关内容
- 无关内容

------

| 这是表格 | 若干项 | 某项 |
| -------- | ------ | ---- |
|          |        |      |
|          |        |      |
|          |        |      |

接下来是引用

> 作者：许怀仁
>
> > 作者：许怀仁
> >
> > > 作者：许怀仁

接下来是网络上的图像

![](https://gss0.baidu.com/70cFfyinKgQFm2e88IuM_a/baike/pic/item/77094b36acaf2eddb8f23230831001e9380193e3.jpg)

跳转文档

[下一个文档](./WH.md)
