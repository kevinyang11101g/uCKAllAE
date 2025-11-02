# 前言

欢迎来到基于SSM（Spring、SpringMVC、MyBatis）的高校提案管理系统项目。本项目旨在为高校提供一个便捷、高效的提案管理平台，助力高校管理工作的高效开展。以下是本项目的详细介绍。

## 内容介绍

本项目是一款基于Java语言和SSM框架的高校提案管理系统。系统主要功能包括：提案提交、提案审核、提案查询、提案统计等。通过本系统，可以有效提高高校提案管理的规范性和效率，方便师生之间的沟通与协作。此外，系统采用Vue前端框架，实现了前后端分离，提高了用户体验。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是本项目中的一个核心代码片段，展示了如何使用MyBatis实现提案的查询功能：

```java
// ProposalMapper.java
public interface ProposalMapper {
    @Select("SELECT * FROM proposal WHERE id = #{id}")
    Proposal selectProposalById(@Param("id") int id);
}

// ProposalService.java
@Service
public class ProposalService {
    @Autowired
    private ProposalMapper proposalMapper;

    public Proposal getProposalById(int id) {
        return proposalMapper.selectProposalById(id);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/324145/13/12731/204770/68b17647Fd80d377b/2418a083f085dd90.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/338656/31/3499/52002/68b1761fF1aaf7c2a/77f685ba22b5d869.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326318/35/12860/147702/68b17620Feceff43a/eba41873dce0f78e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/330661/12/6130/66900/68b17620Fff36d39e/8544ec30f4c0b18a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327998/29/12926/46995/68b17620F8e6b3de3/169c7f60db73214f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329688/39/5912/69830/68b17621Fe633c7ba/5ee374e106468797.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/340662/21/3571/84941/68b17621Feac6ad87/c31620bff6aa08f7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/333485/2/5913/86926/68b17622F02c9c049/036105e741f3e3cb.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339699/34/3145/153355/68b17622F961b75b1/4169f1f4a4a36449.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/334151/13/6020/49550/68b17622F53aab76f/773492c555dd01b1.jpg)

