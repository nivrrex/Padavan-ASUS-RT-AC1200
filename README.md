# Padavan-ASUS-RT-AC1200
Padavan for ASUS RT AC1200

# 说明
使用 https://github.com/hanwckf/rt-n56u 的源码进行编译

hanwckf 对 RT-AC1200 已经不再继续支持，源码放在了.unsupported中

这里是将 https://bitbucket.org/padavan/rt-n56u 和 hanwckf 的源码合并后，进行了编译

可以编译通过，2.4G和5G正常使用，没有额外的插件，具体编译参数详见 configs 文件夹

# 编译方法及命令
将configs文件夹复制到 hanwckf 源码下的 trunk 下同名文件夹

具体编译步骤详见 https://github.com/hanwckf/rt-n56u 说明

```
cd /opt/rt-n56u/trunk
fakeroot ./build_firmware_modify RT-AC1200
```
