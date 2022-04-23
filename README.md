## GS分析学习笔记

### 此笔记为学习GS的纪录

1.下载sratoolkit


```python
# 下载
wget https://ftp-trace.ncbi.nlm.nih.gov/sra/sdk/2.11.3/sratoolkit.2.11.3-ubuntu64.tar.gz
# 解压文件
tar xzvf sratoolkit.2.11.3-ubuntu64.tar.gz
# 添加环境变量到bashr文件中
export PATH=~/root/gs/sratoolkit.3.0.0-centos_linux64/bin:$PATH
# bashr文件在/root目录下，可以通过ls-al命令在root目录下查看
# 应用环境
source ~/.bashrc
# 配置sratoolkit
vdb-config --interactive
# 修改的项目为prefer SRA lite files with simplitied base
```
[]()
2. 
