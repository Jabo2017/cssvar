# css 也有变量了神奇不

## 定义变量


### 全局

:root {
    --bgColor: #f00;   //变量
}


body {
    background-color: var(--bgColor); //调用
}


### 局部变量

.modelInner {
    --fontColor: yellow;
}

//p 在 modelInner 下

p {
    color: var(--fontColor);
}
