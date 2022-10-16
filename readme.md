## CVE-2022-26134_RCE

## 安装

```
git clone https://github.com/yigexioabai/CVE-2022-26134-cve1.git
cd CVE-2022-26134-cve1
pip3 install -r requirements.txt


把CVE-2022-26134_RCE.py放到pocsuite3\pocs目录下
cd pocs
```

## pocsuite3使用

单个url:

```
pocsuite -r CVE-2022-26134_RCE.py -u url
```

多个url:

```
pocsuite -r CVE-2022-26134_RCE.py -f url.txt(url在的文件) --verify
```



## 免责声明🧐

本工具仅面向合法授权的企业安全建设行为，如您需要测试本工具的可用性，请自行搭建测试环境。

在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。请勿对非授权目标进行扫描。

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。