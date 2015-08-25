第五十章 最简单的逻辑判断
===

其实我是连续写的，所以还没醒酒，刚才攥着酒瓶子口拧了半天，才发现根本没盖子。

你问我这状态能说明白不？我问你一加一你能立刻反应不？其实不能，一般我们都会愣一下，不是因为太简单了，而是因为这只是我们从来不用，真尼玛要思考一下。你看我还能做这么复杂的逻辑思维呢，噗，给你开玩笑呢，我写一遍，后期检查一遍，然后规整格式一遍，放心吧你，容易么我。

最简单的逻辑就是 if 判断，这个很像什么呢？就是我们刚讲过去的响应式的媒体查询，媒体查询是当达成了他的条件则执行它内部的 CSS。那么 if 判断就是如果达成小括号里的条件则执行大括号里的语句。

```
if(要判断的条件){
	如果条件为 ture 则执行这部分
}
```

这个其实很好理解，就是如果条件成立，大括号里的与句就在执行，否则就跳过而以。你稍微会点英文就明白，根本就是如果怎样就如何而已。来来，我给大家举个例子：

```
a = 1
if（a==1）{
	alert("a 真的等于 1 耶！");
}
```

那么因为条件成立，所以语句得以执行。就是这个意思。那么如果你在相反的条件下执行什么的话，你当然可以去写 `if(a!=1){……}`，但是如果我们需要判断条件之后，如果条件成立则执行某程序，否则则执行另一段程序呢？其实真的就像我们说英文一样的：

```
a = 2
if（a==1）{
	alert("a 真的等于 1 耶！");
}else{
	alert("a 竟然不等于 1 啊！");
}
```

如果……否则……就这么简单的逻辑，难吗？？？但是他真的很难强大！真的，我不骗你！

然后注意到没有？有几行没有分号耶~因为大括号本身就标志了起始，已经不会引起混乱了，所以最后没有分号。

如果到这里你都看懂了，那么恭喜你，你离入门不远了，现在我给你们留个作业，试着用现在学到的知识去写一个小练习，开发思维哦~看谁写得更加厉害一些了~

> **本章代码下载：[本章代码](http://coffee.zji.me/show-code/50.zip)**

---

**本书是收费的，不过交费凭自觉。**价格定义为每人请我喝一杯咖啡（哪种品质的咖啡随意），支付宝账号：

> **alay9999@163.com  （刘源）**

为了让大家阅读方便，本书将在如下站点发布，但最终内容以主站为准：

* 主站首发： http://coffee.zji.me/
* Gitbook: http://codeme.gitbooks.io/easy-web-code-book/
* 简书： http://www.jianshu.com/users/d37eaf3de0ff
* 站酷： http://www.zcool.com.cn/u/12927742

未经本人许可，禁止任何形式转载。相关事宜请联系： dms@zji.me