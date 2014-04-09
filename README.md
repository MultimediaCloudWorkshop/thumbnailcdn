图像缩略图CDN 
============

Image Thumbnail CDN      

（开发阶段）  

### 特点  
- 省心  
  - 再也不用关心缩略图创建、存储、分发、加速和管理了
- 简单  
- 多种缩略图模式  
  - 限定宽度，等比例缩放
  - 限定高度，等比例缩放
  - 限定宽度和高度，等比例缩放
  - 限定宽度和高度，居中裁剪
  - 限定宽度和高度，从顶部裁剪
- 稳定  

### 使用  
- URL
  - http://thumbnailcdn-xxxxxx.elasticbeanstalk.com/image/path  
  - GET 方法  
  - xxxxxx 为用户ID
  - /image/path 为图片的原始路径  
- 参数  
  - width: 缩略图宽度 （可选）
  - height: 缩略图高度 （可选）
  - crop: 裁剪方式 （可选）
    - Center: 居中裁剪
    - North: 从顶部裁剪  
- 返回  
  - 缩略图文件  
- 注意  
  - 参数width和height不能同时缺省  

### 联系  
- 邮件：multimediacloudworkshop@gmail.com
