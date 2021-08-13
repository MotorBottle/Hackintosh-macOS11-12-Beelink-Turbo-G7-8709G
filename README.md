# Hackintosh-Big-Sur-Beelink-Turbo-G7-8709G
98% completed Hackintosh EFI for Beelink turbo g7 8709g tested on Big Sur 11.2  
由osy的冥王峡谷EFI-hac-mini 修改而来，两个机子在usb定制和pci路径上有不少不同，因此仅适用于零刻的Turbo g7，其他机器请不要使用此EFI

此外请暂缓升级到更新的的版本，11.2以上的系统可能需要改用AppleALC来驱动声卡，本人暂时没空测试；macOS12 monterey目前存在显卡驱动问题，请关注osy的hac-mini的issue页跟进

测试支持 Support tested : Big Sur 11.2
 
#### 配置/Hardware info
| 规格     | 详细信息                                                                       |
| -------- | ------------------------------------------------------------------------------ |
| 型号     | 零刻Beelink Turbo G7                                                        |
| 主板     |                                                         |
| 处理器   | Intel Core i7-8709G @ 3.10GHz 四核                                           |
| 内存     | 16 GB ( 混搭2400MHz 8x2G )                                                  |
| 硬盘     | 西数WD SN550                                |
| 显卡     | AMD VEGA M GH ( 4 GB / HBM )                                        |
| 无线网卡 | BCM94360CS2 ( 自行替换 )                                                 |
| 声卡     | 板载                                                                           |
| OC版本   |  Opencore 0.6.9                                                                              |
                               


#### BIOS
1.Secure Boot                [Disabled]  
2.Disk set to AHCI  
3.XMP                        [Enabled]  
4.CFG Lock                   [Disabled]  
5.VT-d                        [Disabled]  

#### 使用/Issues
 1. 无线网卡： 
    如果你使用的是机器原装的网卡，请自行添加相应的驱动
    
 1. 未解决：    
    音频驱动：音频驱动使用的是VooDooHDA万能驱动，但是此驱动在更新版本的系统中可能会失效，如果你使用AppleALC成功驱动声卡欢迎并感谢分享  
    独显驱动：由于新系统的变动，独显尚未适配macOS Monterey，请暂缓升级到macOS12.0及以上版本
