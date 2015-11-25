# Common

轻量的通用组件(A Lightweight Common Component)
---

+ 包引入
	
	```xml
	<dependency>
        <groupId>me.hao0</groupId>
        <artifactId>common</artifactId>
        <version>1.0.5</version>
    </dependency>
	```
	
+ 依赖包，注意引入项目时是否需要**exclude**:

	```xml
	<dependency>
        <groupId>com.github.kevinsawicki</groupId>
        <artifactId>http-request</artifactId>
        <version>6.0</version>
    </dependency>
    <dependency>
        <groupId>com.fasterxml.jackson.core</groupId>
        <artifactId>jackson-databind</artifactId>
        <version>2.4.2</version>
    </dependency>
    <dependency>
        <groupId>joda-time</groupId>
        <artifactId>joda-time</artifactId>
        <version>2.8.2</version>
    </dependency>
	```

+ 工具类介绍:

	+ [Dates](src/main/java/me/hao0/common/date/Dates.java): 日期工具；
	+ [Http](src/main/java/me/hao0/common/http/Http.java): Http请求工具；
	+ [Jsons](src/main/java/me/hao0/common/json/Jsons.java): Json处理工具；
	+ [Page](src/main/java/me/hao0/common/model/Page.java): 分页对象；
	+ [MD5](src/main/java/me/hao0/common/security/MD5.java): MD5工具；
	+ [RSA](src/main/java/me/hao0/common/secruity/RSA.java): RSA工具；
	+ [Fields](src/main/java/me/hao0/common/util/Fields.java): 反射工具；
	+ [Networks](src/main/java/me/hao0/common/util/Networks.java): 网络工具；
	+ [Preconditions](src/main/java/me/hao0/common/util/Preconditions.java): 扩展guava的Preconditions工具；
	+ [Strings](src/main/java/me/hao0/common/util/Strings.java): 字符串工具；
	+ [Xmls](src/main/java/me/hao0/common/xml/Xmls.java): Xml工具；


      