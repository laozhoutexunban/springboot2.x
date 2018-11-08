##课时 3

简介：使用Maven创建SpringBoot2.x应用

自动创建：使用官方的工具创建项目

手工创建:自己整理war包依赖、好处就是知道具体的流程，有助于学习

官方推荐包命名接口，不要使用默认 defaultPackage

官方文档: https://spring.io/guides/gs/spring-boot/

例子：

			com
			 +- example
			     +- myapplication
			         +- Application.java
			         |
			         +- customer
			         |   +- Customer.java
			         |   +- CustomerController.java
			         |   +- CustomerService.java
			         |   +- CustomerRepository.java
			         |
			         +- order
			             +- Order.java
			             +- OrderController.java
			             +- OrderService.java
			             +- OrderRepository.java
	

