## 一键部署 SS+V2Ray-plugin 到 Heroku  [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

> 1. 部署后，应`open app` ，显示`HTTP ERROR 404`，表示部署成功。

> 2. Android 安装 [Shadowsocks](https://github.com/shadowsocks/shadowsocks-android) 和 [v2ray-plugin-android](https://github.com/shadowsocks/v2ray-plugin-android)。

![](https://raw.githubusercontent.com/xiaokaixuan/ss-v2ray-plugin/master/android.png)

> 3. 部署到VPS时，域名变量`DOMAIN`和映射`/root/.acme.sh`可开启TLS。
> ```sh
> /root/.acme.sh/{domain}/fullchain.cer
> /root/.acme.sh/{domain}/{domain}.key
> ```

### 附加

> 1. 一键部署 SS+V2Ray-plugin 到 [KubeSail](https://kubesail.com/template/kaixuan1115/ss-v2ray-plugin/)。

### 参考 
*https://github.com/shadowsocks/v2ray-plugin*

*https://github.com/gfwlist/gfwlist*

