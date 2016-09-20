# biliobs

## 构建步骤
####1 安装vs2013.5_ce_enu最新版
####2 下载安装qt-opensource-windows-x86-msvc2013-5.4.2.exe
####3 下载vs2013的QT插件qt-vs-addin-1.2.5.exe
####4 在vs2013中设置qt
####5 打开biliobs中的biliobs_all.sln
####6 编译
####7 拷贝QT的dll文件其他依赖文件到Debug目录下
```
	w32-pthreads.dll
	swscale-4.dll
	swresample-2.dll

	Qt5Widgetsd.dll
	Qt5Sqld.dll
	Qt5Guid.dll
	Qt5Cored.dll
	postproc-54.dll
	obsglad.dll
	libx264-148.dll

	jansson.dll
	icuuc53.dll
	icuin53.dll
	DSETUP.dll  d3d的库
	avutil-55.dll
	avformat-57.dll
	avfilter-6.dll
	avdevice-57.dll
	avcodec-57.dll
```
####8 把相关的*.effect 拷贝data目录下
	Debug/data/libobs
	Debug/data/obs-filters

### 直播姬基于或引用了以下项目
+ [Qt5](http://www.qt.io/)
+ [obs-studio](https://github.com/jp9000/obs-studio)
+ [openssl](https://github.com/openssl/openssl)
+ [ffmpeg](https://git.ffmpeg.org/ffmpeg.git)
+ [cURL](https://github.com/curl/curl)
+ [jansson](https://github.com/akheron/jansson)
+ [boost](http://www.boost.org/)
+ [netbsd](https://www.netbsd.org/)
