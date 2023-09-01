# filestore
>基于go-zero、gorm实现的轻量级云盘系统
>使用go run core.go -f etc/core-api.yaml启动项目
>用户模块：
    登录、
    注册、
    邮箱发送验证码、
    查询用户详情
    authorization
>文件上传模块：
    文件上传到oss
    用户文件关联存储
    用户文件列表
    文件名称修改
    文件夹创建
    文件删除
    文件移动
    创建分享记录
    获取资源详情
    通过分享记录保存资源
    文件秒传
    使用oss云实现分块上传