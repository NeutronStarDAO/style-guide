# 排版规范

我们为 ICCookbook 制定了基本的写作格式。请在写作时确保您的文章符合以下格式。

<br>

## 1. 换行

标题的上一行必须是空行，即上一部分内容写完后要空一行再写标题。

<br>

## 2. 空格

### 2.1 中英文之间需要增加空格

**正确：**

* 在 LeanCloud 上，数据存储是围绕 `AVObject` 进行的。

**错误：**

* 在LeanCloud上，数据存储是围绕`AVObject`进行的。

* 在 LeanCloud上，数据存储是围绕 `AVObject`进行的。

**完整的正确用法：**

在 LeanCloud 上，数据存储是围绕 `AVObject` 进行的。每个 `AVObject` 都包含了与 JSON 兼容的 key-value 对应的数据。数据是 schema-free 的，你不需要在每个 `AVObject` 上提前指定存在哪些键，只要直接设定对应的 key-value 即可。

例外：「豆瓣FM」等产品名词，按照官方所定义的格式书写。

<br>

### 2.2 中文与数字之间需要增加空格

**正确：**

* 今天出去买菜花了 5000 元。

**错误：**

* 今天出去买菜花了 5000元。

* 今天出去买菜花了5000元。

<br>

### 2.3 数字与单位之间需要增加空格

**正确：**

* 我家的光纤入屋宽带有 10 Gbps，SSD 一共有 20 TB。

**错误：**

* 我家的光纤入屋宽带有 10Gbps，SSD 一共有 20TB。

例外：度 / 百分比与数字之间不需要增加空格：

**正确：**

* 今天是 233° 的高温。

* 新 MacBook Pro 有 15% 的 CPU 性能提升。

**错误：**

* 今天是 233 ° 的高温。

* 新 MacBook Pro 有 15 % 的 CPU 性能提升。

<br>

### 2.4 全角标点与其他字符之间不加空格

**正确：**

* 刚刚买了一部 iPhone，好开心！

**错误：**

* 刚刚买了一部 iPhone ，好开心！

* 刚刚买了一部 iPhone， 好开心！

<br>

### 2.5 双引号周围要加空格

正确：

* 如果想定义 100 个整型变量，怎样定义？ “ int a,b,c,d,e,f,g ...; ” 语句，但 26 个字母不够用了，再用 “ int aa,bb,cc,dd …; ” 语句，如果这样定义下去，得输入多少行代码才能把这 100 个整型变量定义完？所以，为了解决定义 100 个甚至定义更多个整型变量（也可以是其他类型变量）定义的问题，引入了 “ 数组 ” 。

在双引号 “ 的前后各加一个空格，让它更醒目。

<br>

### 2.6 代码的数字和符号之间加空格

```c++
for(i = 0; i <= 9; i++) { // i = 0 ~ 9,把0到9放进数组
    a[i] = i;
}
```

<br>

## 3. 标点符号

### 3.1 不重复使用标点符号

**正确：**

* 德国队竟然战胜了巴西队！

* 她竟然对你说「喵」？！

**错误：**

* 德国队竟然战胜了巴西队！！

* 德国队竟然战胜了巴西队！！！！！！！！

* 她竟然对你说「喵」？？！！

* 她竟然对你说「喵」？！？！？？！！

<br>

## 3.2 全角和半角

**全角**和**半角**是文字的两种显示形式，“全角”指文字字身长宽比为一比一的正方形，而“半角”为宽度为全角一半的文字。现在这两个词通常用来指代计算机中显示的文字。

<br>

### 3.3 使用全角中文标点

**正确：**

* 嗨！你知道嘛？今天前台的小妹跟我说「喵」了哎！

* 核磁共振成像（NMRI）是什么原理都不知道？JFGI！

**错误：**

* 嗨! 你知道嘛? 今天前台的小妹跟我说 "喵" 了哎！

* 嗨!你知道嘛?今天前台的小妹跟我说"喵"了哎！

* 核磁共振成像 (NMRI) 是什么原理都不知道? JFGI!

* 核磁共振成像(NMRI)是什么原理都不知道?JFGI!

<br>

### 3.4 数字使用半角字符

**正确：**

* 这个蛋糕只卖 1000 元。

**错误：**

* 这个蛋糕只卖 １０００ 元。

例外：在设计稿、宣传海报中如出现极少量数字的情形时，为方便文字对齐，是可以使用全角数字的。

<br>

### 3.5 遇到完整的英文整句、特殊名词，其内容使用半角标点

**正确：**

* 乔布斯那句话是怎么说的？「Stay hungry, stay foolish.」

* 推荐你阅读《Hackers & Painters: Big Ideas from the Computer Age》，非常的有趣。

**错误：**

* 错误使用句号：乔布斯那句话是怎么说的？「Stay hungry，stay foolish。」

* 错误使用冒号：推荐你阅读《Hackers＆Painters：Big Ideas from the Computer Age》，非常的有趣。

<br>

## 4. 名词

### 4.1 专有名词使用正确的大小写

大小写相关用法原属于英文书写范畴，不属于本 wiki 讨论内容，在这里只对部分易错用法进行简述。

**正确：**

* 使用 GitHub 登录

* 我们的客户有 GitHub、Foursquare、Microsoft Corporation、Google、Facebook, Inc.。

**错误：**

* 使用 github 登录

* 使用 GITHUB 登录

* 使用 Github 登录

* 使用 gitHub 登录

* 使用 gｲんĤЦ8 登录

* 我们的客户有 github、foursquare、microsoft corporation、google、facebook, inc.。

* 我们的客户有 GITHUB、FOURSQUARE、MICROSOFT CORPORATION、GOOGLE、FACEBOOK, INC.。

* 我们的客户有 Github、FourSquare、MicroSoft Corporation、Google、FaceBook, Inc.。

* 我们的客户有 gitHub、fourSquare、microSoft Corporation、google、faceBook, Inc.。

* 我们的客户有 gｲんĤЦ8、ｷouЯƧquﾑгє、๓เςг๏ร๏Ŧt ς๏гק๏гคtเ๏ภn、900913、ƒ4ᄃëв๏๏к, IПᄃ.。

注意：当网页中需要配合整体视觉风格而出现全部大写／小写的情形，HTML 中请使用标淮的大小写规范进行书写；并通过 `text-transform: uppercase;`／`text-transform: lowercase;` 对表现形式进行定义。

<br>

### 4.2 不要使用不地道的缩写

**正确：**

* 我们需要一位熟悉 TypeScript、HTML5，至少理解一种框架（如 React、Next.js）的前端开发者。

**错误：**

* 我们需要一位熟悉 Ts、h5，至少理解一种框架（如 RJS、nextjs）的 FED。

<br>

### 4.3 链接之间应该增加空格

**用法：**

* 请 [提交一个 issue](#) 并分配给相关同事。

* 访问我们网站的最新动态，请 [点击这里](#) 进行订阅！

**对比用法：**

* 请[提交一个 issue](#)并分配给相关同事。

* 访问我们网站的最新动态，请[点击这里](#)进行订阅！
