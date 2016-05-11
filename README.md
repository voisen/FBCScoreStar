### FBCScoreStart
以星星的样式显示分数

### 截图
![image](https://github.com/SYFH/FBCScoreStart/blob/master/PrintScreen.gif)

### 使用方法
```
ScoreStart *start = [[ScoreStart alloc] initWithFrame:CGRectMake(10, 100, 250, 50)];
start.startColor = [UIColor orangeColor];
start.score = 3;
[self.view addSubview:start];
```

### 注意
在使用时, 视图的宽必须大于高度, 若不符合标准则Crash!

### License
The MIT License (MIT)

Copyright (c) 2016 SYFH

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
