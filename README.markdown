基于sgroschupf/zkclient-0.9(https://github.com/sgroschupf/zkclient/tree/0.9)升级的zkclient

修改点：
1.去掉对log4j的直接依赖。

2.改groupId为：lm.com.101tec

3.改version为1.0

引用方式：

\<dependency><br />
  \<groupId>lm.com.101tec\</groupId><br />
  \<artifactId>zkclient\</artifactId><br />
  \<version>${lm-zkclient.version}\</version><br />
\</dependency>
