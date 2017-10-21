# Hello Github
### This is my first Githud. I am so happy.Hello ereryone! I'm silver!

![qi](http://a3.qpic.cn/psb?/V12UM34U0WbQxL/90osI.iQslfAEmVgPvMRoGygtuM8TPseapDqQ*x8oB8!/c/dPIAAAAAAAAA&ek=1&kp=1&pt=0&bo=UwNTA1MDUwMDORw!&vuin=1824857749&tm=1508580000&sce=60-2-2&rf=0-0)
## logback.xml
```xml
<?xml version="1.0" encoding="UTF-8" ?>
<configuration>
	<appender name="STDOUT" class="ch.qos.logback.core.ConsoleAppender">
		<encoder>
			<pattern>%d{MM-dd HH:mm:ss.SSS} [%thread] %-5level %logger{36} -
				%msg%n</pattern>
		</encoder>
	</appender>
	<root level="debug">
		<appender-ref ref="STDOUT" />
	</root>
</configuration>
## Thanks. 