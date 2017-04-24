# Node.js--问答系统开发分析

## 数据库

### 用户信息(xx)

| 字段 | 名称 | 属性值 | 是否必填 | 备注 |
|-----|------|------|------|------|
| 注册邮箱 | emaoli | emali | Y | 唯一 |
| 昵称 | name | string | Y | 唯一 |
| 密码 | password | number | Y | |
| 联系方式 | photo | number | Y | |
| 年龄 | age | number | N | |
| 出生日期 | birthday | date | N | |
| 职业 | work | string |  N | |

### 问题信息（ans）

| 字段 | 名称 | 类型 | 是否必填 | 默认值 | 备注 |
|------|------|------|------|------|------|
| 问题标题 | title | string | Y | | |
| 问题内容 | context | string | Y | | |
| 提问时间 | time | date | N | 现在时间 | |
| 浏览次数 | viewnumber | number | N | 0 | |
| 点赞次数 | zannumber | number | N | 0 | |
| 回复次数 | return | number | N | 0 | |
| 解决状态 | reslove | boolen | N | flase | |

### 回复信息 (ret)

| 字段 | 名称 | 类型 | 是否必填 | 默认值 | 备注 |
|------|------|------|------|------|------|
| 问题标题 | title | string | Y | | |
| 问题ID | answerID | id | Y | 问题ID | |
| 回复内容 | context | string | Y | | |
| 回复时间 | time | date | N | 现在时间 | |
| 点赞次数 | zannumber | number | N | 0 | |
| 解决状态 | reslove | boolen | N | flase | |

## 页面设计

### 首页 

1. 暂时不做登录和注册（不包括管理员的权限页面），进入index首先是问题列表（所有的问题题目分页列出）点击问题会跳入详细的页面，

  在详细页下方可以简单的提交回复内容但是不可以修改删除等操作;
  
 页面布局：nav：首页，问题;banner:所有问题的列出 ; list: 输入框，按钮
 
 1. 问题列表旁边登录的表单，可以登录、注册，（没有登录的用户可以浏览首页但是不能跳转详细页面）

### 登录

1.

### 注册 
### 提问页面
### 个人主页

### 开发者信息
### 板块分类 
### 错误页面


