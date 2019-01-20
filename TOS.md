我们仅用以下规则进行实时匹配规则，您的通信方向和通信内容我们不会做任何记录



## 防止版权纠纷（禁BT&磁力下载）
正则表达式
> (protocol|\.torrent|peer_id=|info_hash|get_peers|find_node|BitTorrent|announce_peer)

## 防止邮件滥用
正则表达式
> (Subject|HELO|SMTP)

> (^.*\@)(guerrillamail|guerrillamailblock|sharklasers|grr|pokemail|spam4|bccto|chacuo|027168)\.(info|biz|com|de|net|org|me|la)	

## 屏蔽法轮功网站
正则表达式
> (.*\.|| )(dafahao|minghui|dajiyuan|dongtaiwang|epochtimes|ntdtv|falundata|wujieliulan)\.(org|com|net)

## 防止版权纠纷和滥用（禁迅雷下载）
正则表达式
> (.?)(xunlei|sandai|Thunder|XLLiveUD)(.)

## 阻止（儿童）色情、暴力、暗网等
正则表达式
> (.?)(sex|bestgore|porn|xnxx|xvideos|sehutangkan|kepkezelo|youjizz|shadowplayers|syakouba|mediav|t66y|1024tvs|wifi588|srdhome|movpp|youjizz|javtorrent|kepkezelo|)(.)(.onion）
