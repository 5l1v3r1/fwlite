FGFW-Lite
============

A HTTP Proxy server help to get around the Great Firewall. FGFW-Lite dectets websites blocked by GFW automatically, and forward the request to a uncensored proxy server.

Supported parent proxy server: GoAgent, Shadowsocks, snova, SOCKS5 Proxy, HTTP Proxy, HTTP Proxy over SSL.

For windows users, [download](https://github.com/v3aqb/fgfw-lite/archive/master.zip), edit userconf.ini as needed, and run FGFW_Lite.exe.

requirements under openSUSE:

    zypper install python-tornado python-repoze.lru python-futures
    zypper install python-gtk python-vte python-notify  # gui
    zypper install python-M2Crypto  # advanced encryption for shadowsocks
    zypper install python-pyOpenSSL python-gevent  # goagent

goagent https://code.google.com/p/goagent/

shadowsocks https://github.com/clowwindy/shadowsocks

snova https://code.google.com/p/snova/

pybuild https://github.com/goagent/pybuild
