{{indexmenu_n>10}}

# 自定义镜像

## 制作镜像

选中要制作镜像的主机，然后点击制作镜像按钮。填写镜像名称和描述，点击确定即可创建镜像。

输入镜像名称和描述之后，点击确定按钮，即可生成该主机的镜像，此时页面即跳转到镜像管理页面。

自制镜像的价格和生成自制镜像的原镜像一致，例如，自制镜像从UCloud提供的CentOS
6.5上创建，则使用该镜像创建主机免费；若自制镜像从镜像市场的收费镜像创建，则从该自制镜像创建的主机仍然需要收取市场镜像的费用。用户的自制镜像将为用户长久保存在当前地域。

**请确保制作自制镜像前，不要修改系统的关键配置。例如网络相关的配置信息。系统关键配置的修改可能会引起镜像无法制作，或制作的镜像无法启动等一系列问题。**

## 镜像管理

支持修改用户名，备注。

## 从镜像创建主机

可从自定义镜像创建新主机。

注意事项：

  - 本可用区的镜像只能创建本可用区的主机。若需跨可用区创建，请提交工单开通镜像升级到地域级服务权限。
  - 镜像的适用机型限制传承自改自定义镜像的母镜像。例如，该镜像的母镜像是Windows镜像，则无法通过此镜像创建1核的主机，也无法开启网络增强。

## 自定义镜像配额

| 地域  | 配额 |
| --- | -- |
| 北京一 | 10 |
| 北京二 | 30 |
| 上海二 | 30 |
| 广东  | 10 |
| 香港  | 10 |
| 加州  | 10 |
