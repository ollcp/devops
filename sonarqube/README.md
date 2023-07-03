# 1.修改系统参数
```
echo "vm.max_map_count=262144" > /etc/sysctl.conf; sysctl -p
```

# 2.增加目录权限
```
chmod 777 -R sonarqube
```
