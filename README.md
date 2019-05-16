# ss_panel_theme
sspanel主题


https://www.along.party/%E6%9B%B4%E6%8D%A2ss-panel%E5%89%8D%E7%AB%AF%E4%B8%BB%E9%A2%98%E6%A8%A1%E6%9D%BF%E6%95%99%E7%A8%8B-2.html


搭建教程
进入站点目录
以宝塔默认目录举例，注意进入的是/public

cd /www/wwwroot/ss.91vps.club/public
下载主题一
git clone https://github.com/mmmwhy/ss_panel_theme.git tmp && mv tmp/.git . && rm -rf tmp && git reset --hard
其余两个主题我没有修改完，感觉还有点问题。
如果想要试试的话，可以进入https://github.com/mmmwhy/ss_panel_theme.git ，查看ss_template和Shadowsocks-web分支即可

修改nginx配置
