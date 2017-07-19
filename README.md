# LINUX-wechat-X86{
用于部署zabbix微信报警的脚本（二进制） 
--corpid=我们企业里面的id
--corpsecret=这里就是我们Secret里面的id
--agentid= Agentld ID
--msg={ALERT.MESSAGE}   #报警内容
--user={ALERT.SENDTO}   #给发送报警消息的用户
例：shell# ./wechat --corpid=ww8b64beedcxxxxxxx --corpsecret=MUO5ihdLr7Lq_cDHHSmpYVfhIRTvDh0lA7xrxxxxxxx --msg="zabbix server 告警测试" --user=TianChenChao --agentid=1000002
}
