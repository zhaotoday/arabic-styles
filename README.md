## 参考
- http://blog.brain1981.com/453.html
- http://blog.baiwand.com/?post=212
## 背景
国际化市场，二十七国文字，其中免不了“反常态”的语种，比如，阿拉伯语，波斯语，希伯来文等，书写和阅读习惯都是从右向左，所以文字排版也要求是从右向左。

## CSS 的 direction 属性
**该属性指定了块的基本书写方向，以及针对 Unicode 双向算法的嵌入和覆盖方向。**
也就是说定义了direction:rtl的元素，文字的书写方向是从右至左。另外direction还有控制text-align默认值的作用，定义过direction:rtl的元素，如果没有预先定义过text-align，那么这个元素的text-align的值就变成了“right”。

## html 标签 lang 属性
<html lang="ar">

## 布局
可以利用display:inline-block进行顺序布局。

## 字体大小
我们常用的网页正文字体大小，中英文是12px-14px，而这个字体大小对于阿拉伯文字来说就太小了，一般阿拉伯文要设置16px以上才才方便阅读，最常见的是18px。