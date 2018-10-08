# vlusi_jzc

## 项目配置文件

# sss

数据库配置文件位置：/data/database.php

    <?php
    return array(
        'DB_TYPE'   => 'mysql',
        'DB_HOST'   => '127.0.0.1',
        'DB_USER'   => 'root',
        'DB_PWD'   => 'root',
        'DB_NAME'   => 'vlusi_jzc',
        'DB_PREFIX'   => 'jzc_',
        'DB_PORT'   => '3306',
        'DB_CHARSET'   => 'utf8',
    );

会员根据代金卡账号密码进行充值操作接口：
http://localhost:8080/vlusi_jzc/index.php?m=default&c=user&a=user_drop_card
参数：user_name 用户名  
      card_number 卡号
      card_password 密码
