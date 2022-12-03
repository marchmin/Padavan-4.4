# padavan-4.4 #

This project is based on original rt-n56u with latest mtk 4.4.198 kernel, which is fetch from D-LINK GPL code.

- Features
  - Based on 4.4.198 Linux kernel
  - Support MT7621 based devices
  - Support MT7615D/MT7615N/MT7915D wireless chips
  - Support raeth and mt7621 hwnat with legency driver
  - Support qca shortcut-fe
  - Support IPv6 NAT based on netfilter
  - Support WireGuard integrated in kernel
  - Support fullcone NAT (by Chion82)
  - Support LED&GPIO control via sysfs


- Supported devices
  - CR660x
  - JCG-Q20
  - JCG-AC860M
  - JCG-836PRO
  - JCG-Y2
  - DIR-878
  - DIR-882
  - K2P
  - K2P-USB
  - NETGEAR-BZV
  - MR2600
  - MI-4
  - MI-R3G
  - MI-R3P
  - R2100
  - XY-C1
  - GHL(from https://github.com/fangenhui520/padavan-4.4, 没有机器测试，自行判断)
  - EA7500(from https://github.com/MNM28/padavan-4.4, 没有机器测试，自行判断)
  - R6800(from https://github.com/MNM28/padavan-4.4, 没有机器测试，自行判断)
  - TX1801 Plus(from https://github.com/MNM28/padavan-4.4, 没有机器测试，自行判断)
  - RE-CP-02(无线宝鲁班, from https://github.com/240038901/padavan-4.4, 没有机器测试，自行判断)
  - NEWIFI3(from https://github.com/GH-X/padavan-4.4, 必须拆除主板上编号为C48的电容(位于CPU旁边), 否则外网(WAN)将不能正常工作)
  - MI-R4A(from https://github.com/vipshmily/padavan-4.4, 没有机器测试，自行判断)
  - ~~MT1300(from https://github.com/wifiway520/padavan-4.4, 大佬说不稳定，配置文件不成熟，删了)~~
  
固件默认wifi名称 

2.4G：机器名_mac地址最后四位，如K2P_9981

5G：机器名_5G_mac地址最后四位，如K2P_5G_9981

wifi密码

1234567890

固件后台管理地址:

192.168.2.1

user: admin

password: admin
