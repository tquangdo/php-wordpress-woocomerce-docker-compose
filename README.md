# php-wordpress-woocomerce-docker-compose

![badge4](https://img.shields.io/badge/docker-3.3.1-blue)
![Stars](https://img.shields.io/github/stars/tquangdo/php-wordpress-woocomerce-docker-compose?color=f05340)
![Issues](https://img.shields.io/github/issues/tquangdo/php-wordpress-woocomerce-docker-compose?color=f05340)
![Forks](https://img.shields.io/github/forks/tquangdo/php-wordpress-woocomerce-docker-compose?color=f05340)
[![Report an issue](https://img.shields.io/badge/Support-Issues-green)](https://github.com/tquangdo/php-wordpress-woocomerce-docker-compose/issues/new)

# reference
[youtube](https://www.youtube.com/watch?v=adMfVptgVZo&t=12508s)

# install wordpress
```shell
docker-compose up -d --build
cat /etc/hosts | grep dodeptrai
=>
127.0.0.1       dodeptrai.com
```
- access `dodeptrai.com:8000` on browser => will auto redirect to install page
![install](screenshot/install.png)
- after install wordpress, access `dodeptrai.com:8000` again
![hp](screenshot/hp.png)
- update wordpress latest version=`5.9`
![5_9](screenshot/5_9.png)
- access `dodeptrai.com:3001` on browser => will see `wordpress.wp_users`
![phpmyadmin](screenshot/phpmyadmin.png)

# install elementor
[elementor](https://sinhgiang.com/elementor)
![elementor](screenshot/elementor.png)

# install Loco Translate

# setting admin page
- menu `options > general`
![ad_opt](screenshot/ad_opt.png)
1. ## astra
- install theme `astra`
![astra](screenshot/astra.png)
- click `install plugin ...`(OR`Appearance > Starter Templates`) > select `elementor`
![astra_ele](screenshot/astra_ele.png)
1. ### tech
    - select `online shop > tech start`
    ![astra_tech](screenshot/astra_tech.png)
    - result after imported
    ![astra_res](screenshot/astra_res.png)
1. ### cosmetics
    - search `cosmetics` > select template [cosmetics-store](https://websitedemos.net/cosmetics-store-02/)
    - result after imported
    ![cosmetics_res_1](screenshot/cosmetics_res_1.png)
    --
    ![cosmetics_res_2](screenshot/cosmetics_res_2.png)

# install woo
- `plugin > install new plugin > woo`
![woo](screenshot/woo.png) 
