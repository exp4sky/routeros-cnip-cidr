## RouterOS CN IP List

## To use

```Ros Shell
# CDN, fast cdn下载
/tool fetch url="https://cdn.jsdelivr.net/gh/exp4sky/routeros-cnip-cidr/dist/cn_ip_cidr.rsc" dst-path=cn.rsc;

# if CDN does't work, use this  有科学环境直接下载
/tool fetch url="https://raw.githubusercontent.com/exp4sky/routeros-cnip-cidr/master/dist/cn_ip_cidr.rsc" dst-path=cn.rsc;

/import file-name=cn.rsc;
```

## Tanks to

[ispip.clang.cn](https://ispip.clang.cn/)
