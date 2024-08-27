# OneApp
## 软件功能
此软件仿照OneApp打造，同时适用于android端手机，实现了主页面日推、日推日期选择、音频、个人主页、头像上传等功能，使用爬虫从one接口获取日推数据。
## 环境
android studio导入，等待gradle下载完毕后build项目
## 代码目录架构
│  
└─com
    └─example
        └─finaltermhomework
            ├─activity
            │      LoginActivity.java 登录
            │      MainActivity.java 主页面
            │      ProtocolActivity.java 加密界面
            │      
            ├─fragment
            │  │  MineFragment.java
            │  │  
            │  ├─DiscoverFragment 发现页面，包含日推三个项目
            │  │      DiscoverFragment.java
            │  │      GetReadings.java
            │  │      NumberPickFragment.java
            │  │      ReadingActivity.java
            │  │      ReadingItem.java
            │  │      
            │  ├─HomeFragmentPackage 个人主页
            │  │      CoverFragment.java
            │  │      GetPages.java
            │  │      HomeFragment.java
            │  │      MyViewPagerAdapter.java
            │  │      PageContent.java
            │  │      PageCover.java
            │  │      PageFragment.java
            │  │      PageUpdateTask.java
            │  │      
            │  └─RadioFragment 音频
            │          GetAudio.java
            │          NumberPickFragment.java
            │          RadioFragment.java
            │          RadioItem.java
            │          
            ├─Login 登录
            │      Login.java
            │      User.java
            │      
            ├─LoginBoardcast 登录的广播
            │      LogoutBroadcastReceiver.java
            │      
            └─request 封装了get和post请求，以及response各个部分
                    Callback.java
                    Communication.java
                    Response.java
                    statusCode.java
                    Task.java
                    
## 许可证
apache license
## 联系方式
mashufu@outlook.com

        
