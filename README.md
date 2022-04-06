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
![install](screenshots/install.png)
- after install wordpress, access `dodeptrai.com:8000` again
![hp](screenshots/hp.png)
- update wordpress latest version=`5.9`
![5_9](screenshots/5_9.png)
- access `dodeptrai.com:3001` on browser => will see `wordpress.wp_users`
![phpmyadmin](screenshots/phpmyadmin.png)

# install elementor
[elementor](https://sinhgiang.com/elementor)
![elementor](screenshots/elementor.png)

# install Loco Translate

# setting admin page
- menu `options > general`
![ad_opt](screenshots/ad_opt.png)
1. ## astra
- install theme `astra`
![astra](screenshots/astra.png)
- click `install plugin ...`(OR`Appearance > Starter Templates`) > select `elementor`
![astra_ele](screenshots/astra_ele.png)
1. ### tech
    - select `online shop > tech start`
    ![astra_tech](screenshots/astra_tech.png)
    - result after imported
    ![astra_res](screenshots/astra_res.png)
1. ### cosmetics
    - search `cosmetics` > select template [cosmetics-store](https://websitedemos.net/cosmetics-store-02/)
    - result after imported
    ![cosmetics_res_1](screenshots/cosmetics_res_1.png)
    --
    ![cosmetics_res_2](screenshots/cosmetics_res_2.png)

# install woo
- `plugin > install new plugin > woo`
![woo](screenshots/woo.png)
1. ## giao hang
    - setting `khu vuc giao hang > dong gia/mien phi`:
    - 1. setting
    ![kvgiaohang_1](screenshots/kvgiaohang_1.png)
    - 2. result
    ![kvgiaohang_2](screenshots/kvgiaohang_2.png)
    - setting `Loại hình giao hàng`
    ![lhgiaohang](screenshots/lhgiaohang.png)
1. ## thanh toan
    - setting `Chuyển khoản ngân hàng`
    ![ck](screenshots/ck.png)
    - setting `Trả tiền mặt khi nhận hàng`
    ![cod](screenshots/cod.png)
    - setting `paypal`
    ![paypal](screenshots/paypal.png)
1. ## email
    - click `Bấm vào đây để xem cách email hiển thị như nào.`
    ![mail_ava](screenshots/mail_ava.png)

# Sản phẩm
1. ## đơn giản
    ![sp_dg](screenshots/sp_dg.png)
1. ## biến thể
    - setting
    ![sp_bt_1](screenshots/sp_bt_1.png)
    - result
    ![sp_bt_2](screenshots/sp_bt_2.png)
1. ## nhóm
    - setting
    ![sp_nhom_1](screenshots/sp_nhom_1.png)
    - result
    ![sp_nhom_2](screenshots/sp_nhom_2.png)
1. ## liên kết
    - setting
    ![sp_lk_1](screenshots/sp_lk_1.png)
    - result
    ![sp_lk_2](screenshots/sp_lk_2.png)
1. ## ảo
    - setting
    ![sp_ao_1](screenshots/sp_ao_1.png)
    - result
    ![sp_ao_2](screenshots/sp_ao_2.png)
1. ## tải xuống
    - setting
    ![sp_dl_1](screenshots/sp_dl_1.png)
    - result
    ![sp_dl_2](screenshots/sp_dl_2.png)
