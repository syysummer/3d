##### [API文档地址](https://registry.khronos.org/webgl/specs/1.0/)

##### webgl的常用缓冲区
```
1. 顶点缓冲区
2. 索引缓冲区
3. 纹理
4. 帧缓冲
5. 深度缓冲区
6. 颜色缓冲区
7. 模板缓冲区
```
##### webgl的常用矩阵
```
1. 模型矩阵
2. 观察矩阵
3. 投影矩阵
4. 视口
```

##### webgl绘制图的过程
1. 定义顶点着色器代码和片元着色器代码；
2. 定义绘制相关变量；
3. 初始化承载容器；
4. 创建顶点着色器和片元着色器createShader，绑定shderSource并编译shader。 (加上容错判断);
5. 创建程序对象 createShader，attachShader,linkProgram, (容错判断)，useProgram;
6. 定义顶点缓冲区数据及索引缓冲区数据，将数据与着色器中变量绑定，数据和缓冲区绑定；
7. 绘制图形，顶点缓冲区赋能，绘制；