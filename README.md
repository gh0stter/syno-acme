# syno-acme
通过acme协议更新群晖HTTPS泛域名证书的自动脚本

使用方法参见: [http://www.up4dev.com/2018/05/29/synology-ssl-wildcard-cert-update/](http://www.up4dev.com/2018/05/29/synology-ssl-wildcard-cert-update/)

# 更新
由于原作者许久不更新，遂fork并更新了脚本

更新到最新的acme v3 (目前v3.0.2)，由于v3之后默认CA改成了ZeroSSL，脚本也进行了相应的更新
请参考 [ZeroSSL.com CA](https://github.com/acmesh-official/acme.sh/wiki/ZeroSSL.com-CA)

此版本只支持DMS7，如需DMS6请下载脚本后自行修改
