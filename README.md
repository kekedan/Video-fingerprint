# Video-fingerprint
视频指纹提取服务端
硬件：TINY210 系统：qt4
利用V4L框架采取视频帧然后利MFC压缩编码为H.26传PC客户端，同时将压缩的H.264解码提取每一帧的灰度值，然后采用ORB算法提取帧图像指纹信息传回客户端
实现视频指纹实时提取。
