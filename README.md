# CVE-2014-6271.py
> 写了个脚本，实现中使用的是未封禁的GOOGLE的IP，因此不用翻墙就能直接使用。

## 实现功能
1. goolge批量检测BASH漏洞;
2. 对给定URL进行EXPLOIT;
3. 统计功能，大概就是了解下BASH漏洞的概率，测试了下，差不多500个URL才出一个可利用的BASH漏洞的URL;
4. 把具有漏洞的URL写入文件。

## 使用方法：python CVE-2014-6271.py -h 帮助文档
```
usage: python CVE-2014-6271.py -d google_search
       python CVE-2014-6271.py -u url -e command

optional arguments:
 -h, --help  show this help message and exit
 -u URL      Specific a target URL
 -d DORK     Custom Google Dork,Using Google Search to find targets
 -s START    Crawl Google Page start index
 -c COUNT    Crawl Google Page total count
 -e CMD      Command to Execute
```
