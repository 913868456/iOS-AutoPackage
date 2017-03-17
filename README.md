## 只打包ipa文件

-  下载build.sh文件              
-  修改工程目录为你的项目   `projectPath=你的工程目录`
-  配置编译模式                     `buildConfig="Debug"  ` 或 `buildConfig="Release"`
-  定位到脚本目录,运行脚本   `sh build.sh`

## 打包ipa文件并且上传到fir.im
-  下载build_upTofir.sh文件   
-  检测ruby版本 `ruby -v`  ruby版本需大于1.9.3, 不满足更新ruby
-  安装fir.im插件  `gem install fir-cli`
-  定位到脚本目录,运行脚本  `sh build_upTofir.sh`  
