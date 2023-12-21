# Teaching Toolbox（教学工具箱）一款适用于教学的工具箱

## 介绍
Teaching Toolbox（教学工具箱）是一款使用于教学的工具箱，可以实现教学的便捷功能，有时需要用到一些工具来辅助教学，比如布置作业，随机抽取同学等，这款工具箱可以帮助教师快速地调用这些工具。

## 主要功能
- 随机抽取学生：教师可以在班级中随机抽取一定数量的学生进行回答问题、完成作业等。

- 布置作业：教师可以在工具箱中提前布置作业，并在需要的时候一键发送给学生。

- 屏幕保护：可以在自习时开启，方便学生掌握时间学习。

## 使用方法
1. 下载Teaching Toolbox，或者源代码（如果为本地源代码Python运行需要自行安装sv-ttk库文件，否则程序无法运行）

    ## Windows安装sv-tkk
        pip install sv-tkk

    ## macOS安装sv-tkk
        pip3 install sv-tkk

2. 打开Teaching Toolbox，开始教学吧！
    
    ## 关于配置
    Teaching Toolbox的配置文件为promptjson，配置文件中包含每日一言的语句，在wallpaper文件夹里就是平时使用的屏保的背景图片，homework文件夹就是作业的存储地址，当然这是按照你当前放置module的位置来定的这些文件都是在module文件夹中，如果你需要移动这些文件夹的位置，请一同移动Teaching Toolbox否则他们将无法正常运行。

    ## 如何配置每日一言
    <pre>
    <code class="json">
    {
        "sayings": [
        "今天也是元气满满的一天！",
        "人生的目的在于努力成为一个更好的人。",
        "不要停止奔跑，因为这里就是终点。"
        ]
    }
    </code>
    </pre>

    语句的读取是按照你配置的json来定的，当然可以选择默认配置
    ## 如何配置随机抽取人名
    <pre>
    <code class="Python">
    def random_pick(): 
        global chose_name
        names=['Python','Java','C++','C#','Swift''Kotlin'] 
    </code>
    </pre>
    按照naems格式填写名字，就可以完成配置，当然这目前是初版，后续会打开外部文件读取人名列表抽取（目前这个方法只适用于Python源代码运行）
## 优势
使用教学工具箱可以大幅提高教师的教学效率，让教师有更多的时间和精力关注学生的学习情况，同时也可以提高学生的学习兴趣和积极性。

## 声明 statement

### 2023 Teaching Toolbox. All rights reserved.

### Software development by 猫羽今天吃什么

### Web development by 猫羽今天吃什么

## 版权为开发者所有，禁止用于商业用途，仅供学习参考

### The copyright is owned by the developer, it is prohibited for commercial use, and is for learning reference only
