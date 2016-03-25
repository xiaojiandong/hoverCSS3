# hoverCSS3
hover与CSS3的动画效果

## 效果1：倾斜旋转
```less
   &:hover{ // hover动画
    .top-left-shadow{
      top: -90px;
      left: -94px;
    }
    .bottom-right-shadow{
      top: 17px;
      left: 75px;
    }
    .hello-world-1{
      -webkit-animation:helloWorldAnimate1 0.8s 0.3s backwards;
      -webkit-opacity:1;
    }
    @-webkit-keyframes helloWorldAnimate1{
      0%{
        -webkit-transform: rotate(0deg) scale(0);
      }
      100%{
        -webkit-transform: rotate(360deg) scale(1);
      }
    }
  }
```
![image](https://github.com/xiaojiandong/hoverCSS3/blob/master/%5B%22img%22%5D/animate1.png)
## 效果2：滚动居中
![image](https://github.com/xiaojiandong/hoverCSS3/blob/master/%5B%22img%22%5D/animate2.png)
## 效果3：下拉菜单
![image](https://github.com/xiaojiandong/hoverCSS3/blob/master/%5B%22img%22%5D/animate3.png)
## 效果4：掷骰子
![image](https://github.com/xiaojiandong/hoverCSS3/blob/master/%5B%22img%22%5D/animate4.png)
```less
.welcome2{
      top:55%;
      -webkit-animation:welcome2Animate .7s .8s backwards;
    }
    @-webkit-keyframes welcome2Animate{
      0%{
        -webkit-transform: translateY(0px);
      }
      50%{
        -webkit-transform: translateY(-140px);
      }
      100%{
        -webkit-transform: translateY(0px);
      }
    }
```
