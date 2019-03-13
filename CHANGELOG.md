# Changelog

更新日志

## 0.4.1 - 2019-03-13

### Added

* 增加命令行界面（CLI）, 使用 `./Fuck学习强国 --help` 查看帮助

* 增加使用指定用户ID（作用是区分用户，保存cookies，可随便填写）的多用户模式，使用 `--user=<user_name>` 命令行选项启用： `./Fuck学习强国 --user=abc`

## 0.4.0 - 2019-03-13

### Added

* 增加多开功能（多用户模式），使用 `--multi-user` 命令行选项启用 （不保存cookies，再次打开需要重新登录）

### Fixed

* 解决登录有效期只有6个小时的问题（cookie的有效期只有6个小时）

## 0.3.0 - 2019-03-12

### Added

* 支持使用用户名和密码登录

### Fixed

* 登录界面二维码居中显示