Kangle web server 3.5.X
-------
3.5 基础下兼容主机模板 新增/修复功能 注意: Linux only/HTTP3 可能要更长时间后才能支持

安装教程
-------
<a href="https://github.com/Kazuki-yiji/kangle/releases" target="_blank">下载解压kangle.zip</a>覆盖即可 运行方法和主分支无差异  
Debian / Ubuntu:  
apt update && apt install -y zlib1g libsqlite3-0 libpcre3 libssl1.1 libzstd1 libbrotli1 libstdc++6 libgcc-s1 libc6  
CentOS / Rocky / RHEL:  
dnf install -y zlib sqlite pcre openssl-libs libstdc++ libgcc glibc libzstd brotli

kangle web server 更新日志
-------
2026-09-17 kangle 3.5.26.001  
修复HTTP2漏洞若干(CVE-2026-49975...)  
从主分支移植ZSTD HTTP支持  
为kwaf新增验证码支持
