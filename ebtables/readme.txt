#######################################################################################
	1.ebtables �������ں�ģ�飺

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
Ӧ�����豸������ʱ�� ������Щģ��
#######################################################################################
	2.makefile_eg�ļ���һ��ʹ��ebtables��װ��������

#######################################################################################
	3.���ʹ��makefile��װ��ʱ������฽�����ļ�������ʹ���ļ����µ� makefile�滻ԭmakefile