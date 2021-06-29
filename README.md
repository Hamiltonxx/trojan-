# trojan一键脚本
由于acme.sh把默认的CA从letsencrypt改成zerossl,导致一键脚本安装证书失败。为了避免麻烦,仍旧把server指到letsencrypt


又能愉快地
```
curl -O https://raw.githubusercontent.com/Hamiltonxx/trojan-/main/trojan_mult.sh && chmod +x trojan_mult.sh && ./trojan_mult.sh
```