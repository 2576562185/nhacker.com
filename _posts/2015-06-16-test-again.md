---
layout: post
title: "再次测试"
keywords: ["test", "测试"]
description: "再次测试，测试项目多一些"
category: "临时"
tags: ["temp"]
---
{% include JB/setup %}

各种测试，包括贴图、标签、分类等。  
贴图2：  
![logo效果图](https://github.com/2576562185/nhacker.com/blob/gh-pages/_posts/images/logo.png?raw=true)

代码表示方式：  

    #include<stdio.h>  
    int main(void)  
    {  
         printf("Hello World\n");  
         return 0;  
    }

{% highlight c lineno %}
#include<stdio.h>  
int main(void)  
{  
    printf("Hello World\n");  
    return 0;  
}
{% endhighlight %}

这种，比较麻烦，但由于用的是liquid语法，不受markdown引擎的影响。

```c
#include<stdio.h>  
int main(void)  
{  
    printf("Hello World\n");  
    return 0;  
}
```
上面这种最好用，嗯，方便还高亮。  
**（可惜markdown引擎改成kramdown后失效了。）**

```
#include<stdio.h>  
int main(void)  
{  
    printf("Hello World\n");  
    return 0;  
}
```

公式：
$$
(x+y)^2=x^2+2xy+y^2
$$

就这样。
