 # 脚本介绍
 
  Trojan多用户管理部署程序的基本功能
  - 在线web页面和命令行两种方式管理trojan多用户
  - 启动 / 停止 / 重启 trojan 服务端
  - 支持流量统计和流量限制
  - 命令行模式管理, 支持命令补全
  - 集成acme.sh证书申请
  - 生成客户端配置文件
  - 支持trojan://分享链接和二维码分享(二维码仅限web页面)


 # 脚本代码
 
 一键更改 Trojan-Panel 面板端口并设置伪装站点
 

```bash
wget -N --no-check-certificate "https://raw.githubusercontent.com/Yunconnect/Trojan_panel_web/master/trojan-web-panel.sh" && chmod +x trojan-web-panel.sh && ./trojan-web-panel.sh
```
