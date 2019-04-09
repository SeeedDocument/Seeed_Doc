# Bazaar CSS demo

### note 样式

```
<div class="tips" style="background-color: #e3efff;height: 97px;">
            <div class="left-icon" style="background-color: #a3c7ff;padding-top: 10px;box-sizing: border-box;height: 100%;width: 38px;text-align: center;float: left;height: 97px;">
                <img src="https://s3-us-west-2.amazonaws.com/static.seeed.cc/seeed/icon/Note.svg" alt="attention icon" style="width: 26px;">
            </div>
            <div class="right-desc" style="margin-left: 15px;width:calc(95% - 38px);float: left;">
                <p style="font-weight: bold;margin-top: 10px;">Note</p>
               <p style="font-size: 14px;">If this is the first time you work with Arduino, we strongly recommend you to see <a href="#" style="text-decoration: underline;color: #007a63;">Getting Started with Arduino</a> before the start.is is the first time you work with Arduino, we strongly recommend you to see </p>
          </div>
    </div>
```


### Tip 样式

```
<div class="tips" style="background-color: #d9f5f3;height: 97px;">
            <div class="left-icon" style="background-color: #83dfd3;padding-top: 10px;box-sizing: border-box;height: 100%;width: 38px;text-align: center;float: left;height: 97px;">
                <img src="https://s3-us-west-2.amazonaws.com/static.seeed.cc/seeed/icon/Tip.svg" alt="attention icon" style="width: 26px;">
            </div>
            <div class="right-desc" style="margin-left: 15px;width:calc(95% - 38px);float: left;">
                <p style="font-weight: bold;margin-top: 10px;">Tip</p>
               <p style="font-size: 14px;">If this is the first time you work with Arduino, we strongly recommend you to see <a href="#" style="text-decoration: underline;color: #007a63;">Getting Started with Arduino</a> before the start.is is the first time you work with Arduino, we strongly recommend you to see </p>
          </div>
    </div>

```


### Danger 样式


```
<div class="tips" style="background-color: #ffdde3;height: 97px;">
            <div class="left-icon" style="background-color: #ff8da4;padding-top: 10px;box-sizing: border-box;height: 100%;width: 38px;text-align: center;float: left;height: 97px;">
                <img src="https://s3-us-west-2.amazonaws.com/static.seeed.cc/seeed/icon/Danger.svg" alt="attention icon" style="width: 26px;">
            </div>
            <div class="right-desc" style="margin-left: 15px;width:calc(95% - 38px);float: left;">
                <p style="font-weight: bold;margin-top: 10px;">Danger</p>
               <p style="font-size: 14px;">If this is the first time you work with Arduino, we strongly recommend you to see <a href="#" style="text-decoration: underline;color: #007a63;">Getting Started with Arduino</a> before the start.is is the first time you work with Arduino, we strongly recommend you to see </p>
          </div>
    </div>

```


### Attention 样式

```
<div class="tips" style="background-color: #ffefd9;height: 97px;">
            <div class="left-icon" style="background-color: #ffc983;padding-top: 10px;box-sizing: border-box;height: 100%;width: 38px;text-align: center;float: left;height: 97px;">
                <img src="https://s3-us-west-2.amazonaws.com/static.seeed.cc/seeed/icon/Attention.svg" alt="attention icon" style="width: 26px;">
            </div>
            <div class="right-desc" style="margin-left: 15px;width:calc(95% - 38px);float: left;">
                <p style="font-weight: bold;margin-top: 10px;">Attention</p>
               <p style="font-size: 14px;">If this is the first time you work with Arduino, we strongly recommend you to see <a href="#" style="text-decoration: underline;color: #007a63;">Getting Started with Arduino</a> before the start.is is the first time you work with Arduino, we strongly recommend you to see </p>
          </div>
    </div>

```


使用方法：

点开后台 html 按钮，复制到对应位置即可。复制后替换对应文字部分，如果文字过多，会超过彩色框，别急，这时候你需要再次点击 HTML 按钮

然后找到刚刚粘贴进去的代码，将

```
<div class="tips" style="background-color: #ffdde3;height: 97px;">

```

中的数字 97 适当改大一点，框框就会变长一点, 注意，改的数字需要一样，比如都改成 120


还需要将下面的另一个 97 也改大一点

```
100%;width: 38px;text-align: center;float: left;height: 97px;">

```