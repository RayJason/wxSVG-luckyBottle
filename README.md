# wxSVG-luckyBottle
 “快乐源泉小瓶子”的微信图文交互  
提供发布在吉珠公众号的源码，在研究尝试中的demo，以及优化后的模板源码。   
代码分析：[图文交互｜“小瓶子”图文交互技术总结](https://mp.weixin.qq.com/s/U2lkKimN_JrZhI0RF5e2fg)
&nbsp;
******
&nbsp;
## 使用方法：
&nbsp;
### item.html  
这个文件是单个“小瓶子”。先在这个文件中替换好图片地址，浏览器测试没问题再进行下一步。  
    
&nbsp;
### 小瓶子模板.html  
模板的代码结构：

    <section
    style="display: flex;
    flex-flow: row wrap;
    align-content: flex-start;
    margin: 40rpx 10rpx;
    text-align: center;"
    >
    <section id="单个瓶子和文字">
        <section id="瓶子（可复用）" style="display: block;width: 100%;">
        <section style="height: 0px;">
            <section id="最后一张图片" style="height: 0px;">
            <svg
                style="background-image: url(*);
                background-size: contain;
                background-repeat: no-repeat;
                background-position: 50% 50%;"
            ></svg>
            </section>
            <section id="第4张图片" style="height: 0px;">
            <svg
                style="background-image: url(*);
                background-size: contain;
                background-repeat: no-repeat;
                background-position: 50% 50%;"
            >
                <animate id="点击动画"></animate>
            </svg>
            </section>
            <section id="第3张图片" style="height: 0px;">
            <svg
                style="background-image: url(*);
                background-size: contain;
                background-repeat: no-repeat;
                background-position: 50% 50%;"
            >
                <animate id="点击动画"></animate>
            </svg>
            </section>
            <section id="第2张图片" style="height: 0px;">
            <svg
                style="background-image: url(*);
                background-size: contain;
                background-repeat: no-repeat;
                background-position: 50% 50%;"
            >
                <animate id="点击动画"></animate>
            </svg>
            </section>
            <section id="第1张图片" style="height: 0px;">
            <svg
                style="background-image: url(*);
                background-size: contain;
                background-repeat: no-repeat;
                background-position: 50% 50%;"
            >
                <animate id="点击动画"></animate>
            </svg>
            </section>
            <section style="padding-top: 100%;height: 0;"></section>
        </section>
        </section>
        <section id="文字">
        文字写这里
        </section>
    </section>
    </section>

复制item.html中替换好的代码，替换id="瓶子"的section。可以使用搜索批量替换。  
将 __小瓶子模板.html__ 中的全部代码复制，打开公众号编辑器，F12进入网站源码，粘贴到相应的位置。  
再修改对应的文字即可。  
&nbsp;
******
&nbsp;  
欢迎关注微信公众号：RayJason  
有任何疑问可以发送邮件至:rayjason@stu.jluzh.edu.cn
