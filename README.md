# SecurityGroup

#### [TODO: springBoot异常处理机制](https://github.com/momokanni/SecurityGroup/blob/master/springBoot%E5%BC%82%E5%B8%B8%E5%A4%84%E7%90%86%E6%9C%BA%E5%88%B6.md) 

## 第二部分 SpringSecurity基本原理  

官方定义：
```
   Spring Security is a powerful and highly customizable authentication and access-control framework. It is the de-facto standard for securing Spring-based applications.  

Spring Security is a framework that focuses on providing both authentication and authorization to Java applications. Like all Spring projects, the real power of Spring Security is found in how easily it can be extended to meet custom requirements
```  
译：Spring Security是一个强大而且可高度自定义的认证和流程控制框架。也是一套保护spring基础应用的安全标准。  
   Spring Security是一个聚焦于对Java应用程序提供认证和授权的框架，和其他spring项目一样，其强大之处在于能够很简单的进行自定义开发

#### springSecurity默认的处理流程  

![默认处理流程](https://github.com/momokanni/SecurityGroup/blob/master/img/process/%E9%BB%98%E8%AE%A4%E5%A4%84%E7%90%86%E6%B5%81%E7%A8%8B.png)  

#### 认证流程(登录)
![认证流程](https://github.com/momokanni/SecurityGroup/blob/master/img/process/%E8%AE%A4%E8%AF%81%E6%B5%81%E7%A8%8B%E6%A2%B3%E7%90%86(%E7%99%BB%E5%BD%95).svg)  

#### 记住我-登录成功处理流程  

![记住我-登录成功处理流程](https://github.com/momokanni/SecurityGroup/blob/master/img/process/%E8%AE%B0%E4%BD%8F%E6%88%91-%E7%99%BB%E5%BD%95%E6%88%90%E5%8A%9F%E5%A4%84%E7%90%86%E6%B5%81%E7%A8%8B.svg)  

#### 记住我-自动登录  

![记住我-自动登录](https://github.com/momokanni/SecurityGroup/blob/master/img/process/%E8%AE%B0%E4%BD%8F%E6%88%91-%E8%87%AA%E5%8A%A8%E7%99%BB%E5%BD%95.svg) 


