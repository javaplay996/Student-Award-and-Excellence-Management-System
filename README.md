﻿基于Vue.js和SpringBoot的学生评奖评优管理系统是一个现代化的解决方案，旨在简化和自动化学生评奖评优的过程。

项目录屏：https://www.bilibili.com/video/BV1nZ421a7zR

### 1. 管理后台

管理后台是系统的核心，通常只有管理员和教师角色可以访问。它提供了以下功能：

#### 1.1 院系信息管理

- **添加/编辑/删除院系**：管理员可以创建新的院系，编辑现有院系的信息，或者删除不再需要的院系。
- **院系信息展示**：展示所有院系的详细信息，包括院系名称、负责人、联系方式等。

#### 1.2 班级信息管理

- **班级创建与管理**：允许管理员创建新的班级，分配班级到特定的院系，以及管理班级信息。
- **班级成员管理**：可以添加、删除或更新班级成员的信息。

#### 1.3 学生成绩管理

- **成绩录入**：教师可以录入学生的成绩，包括课程成绩、考试分数等。
- **成绩查询**：提供成绩查询功能，学生和教师可以查看特定学生的成绩。

#### 1.4 奖学金申请管理

- **申请流程管理**：设置奖学金申请的流程，包括申请条件、申请截止日期等。
- **申请审核**：教师和管理员可以审核学生的奖学金申请，包括查看申请材料、决定是否批准等。

#### 1.5 纪律通报管理

- **纪律事件记录**：记录学生的纪律问题，包括违规行为、处罚措施等。
- **通报发布**：管理员可以发布纪律通报，通知全校或特定院系。

### 2. 用户网页端

用户网页端面向所有用户，包括学生、教师和管理员。它提供了以下功能：

#### 2.1 学生界面

- **成绩查询**：学生可以查看自己的成绩。
- **奖学金申请**：符合条件的学生可以在线提交奖学金申请。
- **查看纪律通报**：学生可以查看全校或院系的纪律通报。

#### 2.2 教师界面

- **成绩录入与修改**：教师可以录入和修改学生的成绩。
- **奖学金申请审核**：教师可以审核学生的奖学金申请。
- **纪律事件记录**：教师可以记录学生的纪律问题。

#### 2.3 管理员界面

- **院系和班级管理**：管理员可以管理院系和班级信息。
- **用户权限管理**：管理员可以设置和修改用户的角色和权限。

### 技术栈

- **前端**：Vue.js，用于构建动态的单页面应用。
- **后端**：Spring Boot，提供RESTful API，处理业务逻辑和数据库交互。
- **数据库**：通常使用MySQL或PostgreSQL存储数据。
- **安全**：使用Spring Security进行用户认证和授权。

### 部署和维护

- **部署**：系统可以在云服务器或本地服务器上部署，使用Docker容器化可以简化部署过程。
- **维护**：定期更新系统，修复安全漏洞，优化性能。

这个系统的设计旨在提高管理效率，确保评奖评优过程的公正性和透明度。通过自动化和数字化，可以减少人为错误，提高整体的工作效率。