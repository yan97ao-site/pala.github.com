--- 
layout: post
title: 批量重排flickr的照片顺序
date: 2012-05-06 18:39:18
categories:
    - 相册
tags:
    - flickr
---
原来所有的照片都放在picasa，不过目前这个服务已经被G+排挤的快死了。前两天Google Drive一出，原来的5块钱每年的服务也没有了，目前是最便宜的是2.49每月，25G。现在picasa免费的1G空间已经被用掉了109%，而且还都是存储的压缩版图片。经过比较与试用，还是决定将所有照片迁移到[flickr](http://www.flickr.com/photos/ztpala)。

flickr是按照上传时间顺序排列照片，好在它是可以修改的，但限制条件是不可以早于账号建立时间。所以为了在把老照片上传后能按从新到旧排列，就必须批量修改老照片的上传时间到账号建立时间以把它们放在最后。

目前flickr网页上只支持单张照片修改上传日期，要批量修改需要用第三方的服务，这里推荐两个：

##[flickr photostream update](http://flickrstream.webzardry.com/)
这个站点可以方便的将某个set，tag下的照片的上传日期修改为拍摄日期。对于拍摄日期大于账号建立日期的照片很是方便。但更老的照片则无法修改。

##[h4ppier](http://www.h4ppy.com/h4ppier-photos-widget.php)
可以将特定照片的上传时间往前或者后挪动若干年，月，日，天。这样就可以修改那些更老的照片。

随着硬盘里的照片越来越多，怎样安全方便的整理备份也越来越重要。有人选择买多个硬盘，有人选择Amazon S3这样的云服务，有人选择flickr这种现成的图片服务，也有人选择上传到自己的虚拟主机，另外还有刻盘的。

[v2ex](http://www.v2ex.com/t/29116)上面也有不少人在讨论这个问题。