# spring 初始化执行顺序

代码后补

经过测试，结论如下

**@PostConstruct < InitializingBean#afterPropertiesSet() <自定义初始化方法**
