# An AdBlock for Weibo.app

I found some unnecessary network activities with [Surge](https://nssurge.com "Surge"). Simply blocked them, the app works fine.

You can put the following lines into `[Rule]` section. Or use my conf file `weibo.conf` for a test.

```
# Weibo Ad Exchange
DOMAIN-SUFFIX,wax.weibo.com,REJECT
DOMAIN-SUFFIX,mobile.sina.cn,REJECT
```

```
# Privacy Protect
DOMAIN-SUFFIX,pingma.qq.com,REJECT
DOMAIN-SUFFIX,reachmax.cn,REJECT
DOMAIN-SUFFIX,miaozhen.com,REJECT
DOMAIN-SUFFIX,imrworldwide.com,REJECT
```

```
# Taobao Exchange
DOMAIN-SUFFIX,adashbc.m.taobao.com,REJECT
DOMAIN-SUFFIX,adashx.m.taobao.com,REJECT
DOMAIN-SUFFIX,nbsdk-baichuan.taobao.com,REJECT
```