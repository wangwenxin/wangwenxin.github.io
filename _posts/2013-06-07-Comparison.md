---
layout: post
title:  "Comparison"
date:   2013-06-07 21:49:12
---

听说今天有暴雨，我当天气预报说说的。
在办公室里呆了一天没什么感觉，出去一看，尼玛。。。
哦哟妈呀。。这暴风暴雨，就这样迎接高考啊。。真是。。
这2天一直在琢磨`focu()`输入和`keydown()`输入，区别了下各自不同的UE

Focus()型，鼠标聚焦文本框时是否为空，有值的情况就隐藏提示语，没有值就显示
{% highlight ruby %}
**$(this).focus(function(){**  
                    $(this).siblings("span").hide();  
                }).blur(function(){  
                        var val=$(this).val();  
                        if(val!=""){  
                            $(this).siblings("span").hide();  
                        }else{  
                            $(this).siblings("span").show();  
                        }     
                });  
        })  
{% endhighlight %}

Keydown()型，判断文本框输入值是否为空，有值的情况就隐藏提示语，没有值就显示。
{% highlight ruby %}
**$(this).keydown(function(){** 
                }).blur(function(){  
                        var val=$(this).val();  
                        if(val!=""){  
                            $(this).siblings("span").hide();  
                        }else{  
                            $(this).siblings("span").show();  
                        }  
                    })  
{% endhighlight %}
>奔不了DX11的游戏，真捉急啊。。我要换一个6pin和24pin线长一点的450W电源！！！
