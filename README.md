## 只打包ipa文件

- 下载`build.sh`文件             
- 修改工程目录为你的项目   `projectPath=你的工程目录`
-  配置编译模式                     `buildConfig="Debug"  ` 或 `buildConfig="Release"`
-  在终端下,定位到脚本目录,运行脚本   `sh build.sh`

## 打包ipa文件并且上传到fir.im
- 下载`build_upTofir.sh`文件      
-  更改工程目录,配置编译模式(同上)
-  配置fir.im Token  `fir p $Export_Path -T 你的fir Token`
-  检测ruby版本 `ruby -v`  ruby版本需大于1.9.3, 不满足更新ruby
-  安装fir.im插件  `gem install fir-cli`
-  在终端下, 定位到脚本目录,运行脚本  `sh build_upTofir.sh`

## **注意:** 
需要修改的参数:  ` projectPath`  `buildConfig` `$Export_Path -T`
