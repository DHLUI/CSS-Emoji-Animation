# Cute-Emoji-Animation

![pic](https://raw.githubusercontent.com/DHLUI/CSS-Emoji-Animation/master/Cute-Emoji-Animation.png)

This is an animation made by HTML/CSS.

### [View the demo here →]()

If you like this Emoji .You can get the code.

```
git clone https://github.com/DHLUI/DHL-Blog-designer.git
```

Below is the main CSS part:

```
  .emoji_container {
        width: 720px;
        height: 900px;
        background: #f3d7c2;
        position: relative;
        overflow: hidden;
        margin: auto;
        margin-top: 90px;
    }
    
    .emoji_container .header {
        width: 100%;
        height: 50px;
        position: relative;
        top: 0;
        left: 0;
    }
    
    .emoji_container .header .header_main {
        width: 160px;
        height: 100%;
        position: absolute;
        right: 0;
        top: 0;
        font-size: 30px;
        overflow: hidden;
    }
    
    .emoji_container .body {
        width: 100%;
        height: 940px;
        position: relative;
        top: 50px;
        left: 0;
    }
    
    .body .eyes {
        position: relative;
    }
    
    .body .eyes .leftEye,
    .body .eyes .rightEye {
        width: 85px;
        height: 85px;
        background: #422707;
        border-radius: 50%;
        position: absolute;
        top: 40px;
    }
    
    .body .eyes .leftEye {
        left: 150px;
    }
    
    .body .eyes .rightEye {
        right: 150px;
    }
    
    .body .eyes .leftEye:after,
    .body .eyes .rightEye:after {
        content: '';
        display: block;
        width: 30px;
        height: 30px;
        background: #fff;
        border-radius: 50%;
        position: absolute;
        top: 10px;
        left: 10px;
        -webkit-animation: eyeMove 3s infinite;
    }
    
    @-webkit-keyframes eyeMove {
        0% {
            top: 10px;
            left: 10px;
        }
        30% {
            top: 10px;
            left: 40px;
        }
        40% {
            top: 10px;
            left: 40px;
        }
        50% {
            top: 10px;
            left: 40px;
        }
        80%,
        90% {
            top: 10px;
            left: 10px;
        }
    }
    
    .body .nose {
        position: absolute;
        width: 32px;
        height: 22px;
        background: #291605;
        border-radius: 36px/36px;
        left: 50%;
        top: 100px;
        margin-left: -18px;
    }
    
    .body .cheek {
        position: relative;
    }
    
    .body .cheek .leftCheek,
    .body .cheek .rightCheek {
        width: 140px;
        height: 140px;
        background: #e1634c;
        border-radius: 60%;
        position: absolute;
        top: 165px;
    }
    
    .body .cheek .leftCheek {
        left: 60px;
    }
    
    .body .cheek .rightCheek {
        right: 60px;
    }
    
    .body .mouth {
        position: relative;
        width: 180px;
        height: 180px;
        left: 50%;
        top: 180px;
        margin-left: -90px;
    }
    
    .body .mouth .mouth_main {
        position: absolute;
        left: 0;
        top: 0px;
        width: 180px;
        height: 180px;
        background: #8c262a;
        border-top-right-radius: 90px;
        border-top-left-radius: 90px;
        border-bottom-left-radius: 250px 200px;
        border-bottom-right-radius: 250px 200px;
        overflow: hidden;
    }
    
    .body .mouth .tongue {
        width: 200px;
        height: 200px;
        background: rgb(221, 102, 106);
        margin-top: 40px;
        margin-left: -10px;
        border-top-left-radius: 100px;
        border-top-right-radius: 100px;
        overflow: hidden;
    }
    
    .body .s {
        position: relative;
    }
    
```      

Hope you like.


## License

Apache License 2.0. Copyright (c) 2016-2017 DHL
    
