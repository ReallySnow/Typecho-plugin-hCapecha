# Typecho验证码插件，使用hCaptcha API 参考[reCAPTCHA插件](https://github.com/D-Bood/reCAPTCHA)
## 使用方法
前往[hCaptcha](https://www.hcaptcha.com/)申请API KEY
激活该插件，并配置Site Key和Serect Key；
插入以下行

    <?php hCaptcha_Plugin::output(); ?>
