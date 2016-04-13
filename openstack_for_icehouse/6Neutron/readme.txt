LinuxBridge 插件支持： flat,FlatDHCP,bridge
OpenVswitch 插件支持： GRE,Vlan,Vxlan


brctl show : 显示关于桥接的信息
ovs-ofctl show <bridge>[br-int]      #显示关于openvswitch插件的桥接
ovs-ofctl dump-flows <bridge>   	 #查看flow的规则
ovs-vsctl show  					 #查看vlan标记