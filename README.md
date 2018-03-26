# CSS3special-effects
CSS3special effects

## light 

* infinite                                           这是循环执行的属性，有了它，才能一闪一闪滴！

* -webkit-text-fill-color: transparent;    文字填充颜色为透明，没有设置的话，看不出白色渐变划过效果的！

* -webkit-background-clip: text;          把文本内容之外的背景给裁剪掉，如果不加，文字显示不出来，只显示渐变的颜色！

* color-stop() 渐变的color-stop              函数，表示渐变的位置和颜色，就是它，我们才能想在哪里渐变就哪里渐变，再让它移动起来，就出现一闪一闪的效果了！

* 思路：
    
        　　* 首先，设置一个中间白色、两边灰色的渐变背景色；
       
        　　* 其次，文字填充颜色设为透明(才能看到白色背景)；
        
        　　* 接着，把文字之外的背景色给裁剪掉(只显示文字)；
        
        　　* 最后，用@keyframes，让背景白色位置循环从左到右执行。