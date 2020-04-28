# login-register
springbot+mybaits登录注册后台代码返回json
用于自己的学习

csdn博客地址https://blog.csdn.net/glc11223344/article/details/105793370

数据库表
DROP TABLE IF EXISTS `usermessage`;
CREATE TABLE `usermessage` (
  `id` int(20) NOT NULL AUTO_INCREMENT,
  `username` varchar(255) COLLATE utf8_unicode_ci DEFAULT NULL,
  `password` varchar(255) COLLATE utf8_unicode_ci DEFAULT NULL,
  `address` varchar(255) COLLATE utf8_unicode_ci DEFAULT NULL,
  `phone` varchar(11) COLLATE utf8_unicode_ci DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM AUTO_INCREMENT=15 DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci;


