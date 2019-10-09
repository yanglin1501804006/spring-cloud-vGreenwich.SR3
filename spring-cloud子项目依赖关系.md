
#spring-cloud各个子项目之间依赖关系  #

如图下载了spring-cloud-vGreenwich.SR2版本的源码：

![image](https://github.com/yanglin1501804006/spring-cloud-vGreenwich.SR2/blob/master/images/spring-cloud-release-vGreenwich.SR2.png)

time:    7/31/2019 2:21:16 PM           
By:       Spring的思念

<font color=#0099ff size=4 face="黑体">1：解压源码</font>

打开该路径spring-cloud-release-vGreenwich.SR2\spring-cloud-dependencies下pom.xml文件

<font color=#0099ff size=4 face="黑体">2：查看spring-cloud之间的依赖关系</font>

		<parent>
		<groupId>org.springframework.cloud</groupId>
		<artifactId>spring-cloud-dependencies-parent</artifactId>
		<version>2.1.6.RELEASE</version>
		<relativePath/>
		</parent>
		<artifactId>spring-cloud-dependencies</artifactId>
		<version>Greenwich.SR2</version>
		<name>spring-cloud-dependencies</name>
		<description>Spring Cloud Dependencies</description>
		<packaging>pom</packaging>
		<properties>
			<main.basedir>${basedir}/../..</main.basedir>
			<spring-cloud-aws.version>2.1.2.RELEASE</spring-cloud-aws.version>
			<spring-cloud-bus.version>2.1.2.RELEASE</spring-cloud-bus.version>
			<spring-cloud-cloudfoundry.version>2.1.2.RELEASE</spring-cloud-cloudfoundry.version>
			<spring-cloud-commons.version>2.1.2.RELEASE</spring-cloud-commons.version>
			<spring-cloud-config.version>2.1.3.RELEASE</spring-cloud-config.version>
			<spring-cloud-consul.version>2.1.2.RELEASE</spring-cloud-consul.version>
			<spring-cloud-contract.version>2.1.2.RELEASE</spring-cloud-contract.version>
			<spring-cloud-function.version>2.0.2.RELEASE</spring-cloud-function.version>
			<spring-cloud-gateway.version>2.1.2.RELEASE</spring-cloud-gateway.version>
			<spring-cloud-gcp.version>1.1.2.RELEASE</spring-cloud-gcp.version>
			<spring-cloud-kubernetes.version>1.0.2.RELEASE</spring-cloud-kubernetes.version>
			<spring-cloud-netflix.version>2.1.2.RELEASE</spring-cloud-netflix.version>
			<spring-cloud-openfeign.version>2.1.2.RELEASE</spring-cloud-openfeign.version>
			<spring-cloud-security.version>2.1.3.RELEASE</spring-cloud-security.version>
			<spring-cloud-sleuth.version>2.1.2.RELEASE</spring-cloud-sleuth.version>
			<spring-cloud-stream.version>Fishtown.SR3</spring-cloud-stream.version>
			<spring-cloud-task.version>2.1.2.RELEASE</spring-cloud-task.version>
			<spring-cloud-vault.version>2.1.2.RELEASE</spring-cloud-vault.version>
			<spring-cloud-zookeeper.version>2.1.2.RELEASE</spring-cloud-zookeeper.version>
	</properties>

一目了然了吧！

spring-cloud-vGreenwich.SR3 版本查看子项目版本配套关系参考spring-cloud-vGreenwich.SR2方法即可。
