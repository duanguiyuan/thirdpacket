#######################################################################################
	1.ebtables 依赖于内核模块：

insmod ebt_802_3.ko 
insmod ebtable_filter.ko  
insmod ebtables.ko   
insmod ebt_arp.ko       
insmod ebt_dnat.ko  
insmod ebt_limit.ko  
insmod ebt_mark.ko    
insmod ebt_nflog.ko    
insmod ebt_redirect.ko  
insmod ebt_stp.ko   ebt_vlan.ko
insmod ebtable_broute.ko  
insmod ebtable_nat.ko     
insmod ebt_among.ko  
insmod ebt_arpreply.ko  
insmod ebt_ip.ko    
insmod ebt_log.ko    
insmod ebt_mark_m.ko  
insmod ebt_pkttype.ko  
insmod ebt_snat.ko      
insmod ebt_ulog.ko
应该在设备启动的时候 加载这些模块
#######################################################################################
	2.makefile_eg文件是一个使用ebtables安装包的例子

#######################################################################################
	3.其次使用makefile安装的时候，有许多附属的文件，可以使用文件夹下的 makefile替换原makefile