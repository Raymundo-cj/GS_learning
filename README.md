## GS分析学习笔记

### 此笔记为学习GS的纪录

1.下载sratoolkit


``` python
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
[参考网站](https://blog.csdn.net/Yuan_CHarLoTTe/article/details/121687024?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522165064034616780271922163%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=165064034616780271922163&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~times_rank-1-121687024.142^v9^pc_search_result_control_group,157^v4^new_style&utm_term=LINUX%E4%B8%8B%E8%BD%BDsratoolkit&spm=1018.2226.3001.4187)

2. linux下samtools的安装与使用

``` python
#下载
wget https://github.com/samtools/samtools/releases/download/1.9/samtools-1.9.tar.bz2
# 解压
tar -xf samtools-1.9.tar.bz2
#进入相应的文件夹
cd samtools-1.9
./configure
make
make install
```
[参考网站](https://blog.csdn.net/Gentlezzx/article/details/121626879?spm=1001.2014.3001.5502)

2. linux下bwa的安装与使用

```python
# 下载软件、
https://github.com/lh3/bwa
之后解压
tar -xf tar -xf bwa-0.7.17.tar.bz2 
#找到下一个目录
cd bwa-0.7.17/
#执行
./bwa
# 即可
```




