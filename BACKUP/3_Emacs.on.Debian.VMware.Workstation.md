# [Emacs on Debian VMware Workstation](https://github.com/zheng7fu2/zheng7fu2.github.io/issues/3)

在Windows 10上运行VMWare Workstation ,安装Debian虚拟机.开启SSH登录.
安装Emacs 27.1 ,Git [chenbin的配置文件](https://github.com/redguardtoo/emacs.d),
安装第三方程序:
 apt install  fortunes-zh w3m  hunspell xmlstarlet imagemagick zip unzip xclip cmake clang pandoc universal-ctags global libreoffice pip sdcv ripgrep sbcl ffmpeg shellcheck mkvtoolnix
在Windows上通过[MobaXterm ](https://mobaxterm.mobatek.net/)终端访问Debian,运行Emacs.


---

安装cnfont 配置中英文对齐.

---

没有字体,安装 fonts-noto 包
 
fonts-hanazono 包  https://salsa.debian.org/fonts-team/fonts-hanazono
http://fonts.jp/hanazono/



---

不能选择区域

---

> 不能选择区域

更换了 [emacs-lucid 版本](https://packages.debian.org/bullseye/emacs-lucid)就好了.  GTK版本有问题.