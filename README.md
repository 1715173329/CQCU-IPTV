## CQCU-IPTV

适用于重庆联通用户的 IPTV 频道列表。

注意：此频道列表无法在 **非重庆联通** 网络环境下使用。

### 文件说明

- cqcu-unicast.m3u / cqcu-unicast-alternative.m3u

  重庆联通单播源，公网或 IPTV 专网均可播放。

  - 没有开通 IPTV 业务的用户也能观看

- cqcu-multicast.m3u

  重庆联通组播源，只能在 IPTV 专网播放。

- cqcu-multicast-udpxy.m3u

  重庆联通组播源，只能在 IPTV 专网播放。

  配置了 udpxy 组播转单播，有助于避免广播风暴或在不支持 rtp 协议的设备上观看。

  请注意按实际情况更改 udpxy 服务器地址与端口。

  - 可能会造成切换频道卡顿

### 配置说明

参考 [重庆联通 IPTV 单线复用 + 内网融合教程](https://blog.imouto.in/post/iptv/2022/cqcu-iptv-on-openwrt/)。
