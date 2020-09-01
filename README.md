# github_search
# fork修改
已经改成循环模式，完成大循环以后会间隔1000秒，再次检索redis进行新一轮搜索。并且新的内容会覆盖旧的内容以保持更新。新的关键字可以通过redis管理面板添加.
### 介绍
根据 keywords 搜索 github 上面的 repos, 并通过 web 展示

### 安装
  * 安装 redis 
  
   > apt-get install redis-server
      
  * 安装依赖
  
  > pip install requirements.txt
  
### run
  * run 搜索结果的脚本
  
  > python github_search.py 

  * 开启 web 服务, 访问 http://127.0.0.1:5000/
  
  > python app.py
  
### 搜索参数配置
  * github_search.py 里面 修改 keywords = ['', '', ''] 可以定制搜索
  
### screenshots

  ![demo](https://raw.githubusercontent.com/facert/github_search/master/screenshots/demo.png)
  
