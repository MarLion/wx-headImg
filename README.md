# wx-headImg
微信小程序实现头像裁剪上传功能
canvas裁剪
上传未使用uoLoadFile API  因为后端人员接口有问题无法解决 使用wx.getFileSystemManager().readFile API转化为base64码 使用wx.request将bae64码作为参数传递（可能会导致图片失真 慎用 这里只实现图片的头像的选择裁剪）；
