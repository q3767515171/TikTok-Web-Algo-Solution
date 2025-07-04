# TikTok web端纯算成品

## 1.数据签名: X-Bogus X-Gnarly

主要用于数据接口的鉴权，校验参数是否正确。

![xb_xg](/Users/cute/Documents/TikTok-web-algo.assets/xb_xg.png)

## 2.日志上报: strData加解密纯算

风控接口，上报浏览器设备信息。

![strData](/Users/cute/Documents/TikTok-web-algo.assets/strData-1600703.png)

## 3.mssdkInfo加解密纯算

登录接口，协议头签名参数，明文主要为设备指纹信息。

![mssdk](/Users/cute/Documents/TikTok-web-algo.assets/mssdk.png)

## 4.验证码v1 滑块/旋转滑块/点选/语音（V2.33.12）

验证客户端是否正常，弹出验证码。

![captcha](/Users/cute/Documents/TikTok-web-algo.assets/captcha.png)

## 5.验证码v2 滑块（V3.0.43）

商品相关接口，对设备进行风控。

![captcha3](/Users/cute/Documents/TikTok-web-algo.assets/captcha3.png)

## 6.其他参数

hashed_id

tt_ticket_guard_client_data

username password 签名

......

## 7.Solution

UVE6IDM3Njc1MTUxNzE=