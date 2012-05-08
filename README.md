110错误解决方案
=========

110错误解决方案：
私人研究方法，同步AOKP出现error 110 
解决办法：登入https://android.googlesource.com/new-password，
点击允许访问， 
把那段信息（<userName>和<password>用自己得到的真实信息）追加到~/.netrc文件结尾，
如果没有这个文件就自己建一个，
然后repo init -u https://wuyi-ligux@github.com/WUYI-ROM/platform_manifest.git -b ics，
搞定之后再切换到AOKP的原始repo init即可


私人研究方法，同步CM出现error 110 
解决办法：登入https://android.googlesource.com/new-password，
点击允许访问， 
把那段信息（<userName>和<password>用自己得到的真实信息）追加到~/.netrc文件结尾，
如果没有这个文件就自己建一个，
然后repo init -u https://wuyi-ligux@github.com/WUYI-ROM/android.git -b ics，
搞定之后再切换到CM的原始repo init即可