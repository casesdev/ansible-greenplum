[ansible-greenplum](https://github.com/uazwu/ansible-greenplum)
=======

**🎉 此项目受用于使用 ansible 快速安装 greenplum 集群。**

- **特别说明：** 此项目目前并不完善，目前仍需要进行完善，个人在仅在 CentOS 8.4 系统上测试成功。请勿再生产环境中使用

- **如何说明：** 
```bash
git clone https://github.com/uazwu/ansible-greenplum.git
cd ansible-greenplum
./ansible/install.sh
# 请配置 example/hosts.greemplum.ini 中的信息
ansible-playbook -i example/hosts.greemplum.ini init-greenplum-cluster.yml
```

## License

MIT