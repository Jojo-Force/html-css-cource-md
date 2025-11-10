

##### 第一课：课程

* 课程内容

1. web design

2. html

3. css

4. responsive design

   

* 静态网页：static website：只有前端，没有后端。

![image-20251110140502382](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110140502382.png)

* 动态网站：Dynamic website：有后端支持，页面内容由后端动态生成。

![image-20251110141301237](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110141301237.png)

* HTML像名词
* CSS像形容词
* JS像动词

![image-20251110141209649](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110141209649.png)

##### 第二课：安装VSCODE

* 安装prettier插件：

![image-20251110141713079](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110141713079.png)

插件作用：每当你保存的时候，会自动格式化你的代码。

* 进入setting，设置默认formatter为prettier：

![image-20251110142129112](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110142129112.png)

* 设置formart on save属性：保存时自动格式化：

![image-20251110142247718](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110142247718.png)

* 自动保存：离开窗口时自动保存文件：

![image-20251110142445129](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110142445129.png)



* tab size设置为2：

![image-20251110142613922](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110142613922.png)



* 安装颜色主题插件：

  ![image-20251110142955893](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110142955893.png)

* 设置主题：

![image-20251110143228543](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110143228543.png)



##### 第三课：写第一个网页

使用！+回车：生成模板

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My first webpage</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>My name is Jojo, and this is my very first webpage :D</p>
  </body>
</html>
```



##### 第四课：HTML

![image-20251110152822610](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110152822610.png)



* 标签

![image-20251110153111064](使用 HTML 和 CSS 构建响应式真实世界网站.assets/image-20251110153111064.png)

* 基本结构

  * 声明

  * html标签

  * head标签

  * body标签

  ```html
  <!DOCTYPE html>
  <html>
    <head>
      <title>The Basic Language of the web: HTML</title>
    </head>
  
    <body>
      <h1>The Basic Language of the web: HTML</h1>
    </body>
  </html>
  
  ```

  

* p标签

  p标签代表段落，一个段落的话放进p标签里。

  

* h1标签

  最佳实践：一个网页里最好只有一个h1标签。

  

* b加粗

  ```html
   <b>Laura Jones</b>
  ```

  最佳实践：别用b，用strong代替，b没有什么含义。

  ```html
  <strong>Laura Jones</strong>
  ```

  

* i斜体

  ```html
  <i>fundamental</i>
  ```

  最佳实践：别用i，用em代替，i没有什么含义。

  ```html
  <em>fundamental</em>
  ```

  
