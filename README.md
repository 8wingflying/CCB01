# CCB01
## 第1單元 資通安全基本觀念
## 第2單元 資通安全相關法規
## 第3單元 資通安全風險管理與業務持續運作管理
## 第4單元 作業安全 == > Operational security (OPSEC)
## 第5單元 資訊委外安全
## 第6單元 存取控制與加解密技術
## 第7單元 網路安全與實體安全

# 設定
- CrowdStrike出包為何掀起史上IT最大癱瘓？https://www.cw.com.tw/article/5131204
  - https://en.wikipedia.org/wiki/2024_CrowdStrike-related_IT_outages 
- TOP 10 Misconfiguration

## 聯絡email
- 8wingflying@gmail.com


## 檢查HTTPs
- https://check.twnic.tw/

# 測試IP
- http://192.168.33.75:8080/WebGoat/login.mvc
- 登入
#### 測試1:String SQL Injection
- String SQL Injection
- 攻擊的Payload == > 1'or '1'='1
- SELECT * FROM user_data WHERE last_name = '    '
- SELECT * FROM user_data WHERE last_name = '1'or '1'='1'
- SELECT * FROM user_data
#### 測試2:Stored XSS Attacks
- 攻擊的Payload == >`  <script>alert("XSS Hacking")<script/> `
- `<script>alert('XSS Vulnerability!')</script>`
