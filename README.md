# What

A [hosts file](https://raw.githubusercontent.com/LGA1150/SYSUv6-hosts/master/hosts) that helps students surf the net smoother, faster and safer in SYSU.

# Why

In Aug 2015, the main ISP of SYSU was replaced by CMCC, which has a heavily restricted "Internet": Speed (1.5 Mbps), Websites, etc. 

But luckily, we still have CHN-UNICOM and CERNET.

# How

This hosts file redirect those affected websites to their CERNET/CHN-UNICOM/IPv6 CDN, to bypass the limitation of CMCC.

# Usage
Replace `%WINDIR%\system32\drivers\etc\hosts` with this hosts file.

If you are using an anti-virus software, you should whitelist it.

You should use [HTTPS Everywhere](https://www.eff.org/https-everywhere/) (Supports Firefox and Chrome) to encrypt your connection.

Common download tools such as QQ XuanFeng, Xunlei and Internet Download Manager are not recommended since they don't support IPv6.

[Free Download Manager 5](http://www.freedownloadmanager.org/landing5.htm) : A multi-threaded download tool which supports IPv6.

# Effects
1.

Default:

![cmcc](https://cloud.githubusercontent.com/assets/9155358/11761091/7eae6bae-a0ef-11e5-8818-759a55bce065.PNG)
Redirect to CERNET CDN:

![cernet](https://cloud.githubusercontent.com/assets/9155358/11761092/82ec596a-a0ef-11e5-866c-aa4b8994db16.PNG)

2.

Default:

![cmcc](https://cloud.githubusercontent.com/assets/9155358/11761130/f290c3f4-a0f0-11e5-843b-b59659dee977.PNG)

Redirect to IPv6 CDN:

![ipv6](https://cloud.githubusercontent.com/assets/9155358/11761131/f56fcdc2-a0f0-11e5-8b67-4bce1a5268ea.PNG)
