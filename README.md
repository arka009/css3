# css3
css3 demos

## nba
纯css3实现图片切换(只兼容webkit内核浏览器)

## loading
loading1通过设置animate-delay为负值来实现
假设整个动画的完成时间是1s, annimate-delay设置的负值为－0.4，那么动画就将跳过0.4s之前的动画，从0.4s这个时间点开始执行动画

loading2的实现很简单，只是设置border-radius将div设置成圆形，再将border－left－color设置成与其他边框不同的颜色，让div旋转即可

loading3只需从0到50%的时候按照y轴旋转180deg，然后在50%到100％之间在按照x轴旋转180deg即可，通过设置perspective实现3维空间的效果

loading4也是旋转360deg，只是transform-origin不再是默认的center center，而是改为元素伪类顶部居中的位置