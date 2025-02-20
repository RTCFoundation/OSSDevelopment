Copyright (c) 2022 [minghuizhou@osslab-pku]  
[OSSDevelopment-course/开源软件开发&技术课程] is licensed under Mulan PSL v2.   
You can use this software according to the terms and conditions of the Mulan PSL v2.   
You may obtain a copy of Mulan PSL v2 at:   
         http://license.coscl.org.cn/MulanPSL2   
THIS SOFTWARE IS PROVIDED ON AN "AS IS" BASIS, WITHOUT WARRANTIES OF ANY KIND,   
EITHER EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO NON-INFRINGEMENT,   
MERCHANTABILITY OR FIT FOR A PARTICULAR PURPOSE.   
See the Mulan PSL v2 for more details.

# 2022年秋冬学期——课程大纲 (subject to change)

**主要内容： 开源开发方法、技术和实践OSP + 开源文化OSC + 上机实习lab  + 课程项目PRJ**

授课教师：周明辉 zhmh@pku.edu.cn     
助教：    何昊 heh@pku.edu.cn      

## 第1次课：开源软件及其开发概述（课堂lecture）  09/07  

* 100课程简介：课程的目的和内容，以及课程的考核形式。  **lecture100**    
* 101开源软件概述：开源的定义、历史和现状、社区结构和治理，以及开源研究。 **lecture101**  

课堂练习：
* 课堂上访问github/gitee/gitlink，设立平台账号，了解一个开源项目。
* 阅读并了解Lab1。

> **Lab 1：练习使用git和GitHub（7分，三周）**
>  - 注册GitHub账号
>  - 加入课程的[Organization](https://github.com/OSS-Dev-Course-PKU)
>  - 创建GitHub仓库并添加commit，于README.md写下目前的开源项目贡献想法
> 
> Lab 1详细要求参见[WriteUp](Assignments/Lab1.md)，**截止日期：2022.09.28 11:59am**

## 第2次课：开源开发的支持平台和关键技术：熟悉开源平台和Git操作（课堂lecture） 09/14      

* 201：Git实践入门   **lecture201**
  - 了解版本控制，了解使用Git，https://missing.csail.mit.edu/2020/version-control/   
* 202：GitHub实践入门     **lecture202**
  - 了解如何用开源协作工具，熟悉Github/Gitee/GitLink--建立账号和代码仓库，浏览和fork项目

> **Lab 1扩展：练习使用issue、fork和PR**
>  - 提交一个issue，描述自己的想法（相比较于第一次提交）做出了哪些变化
>  - 将仓库fork到自己的账号下，对README.md做出相应修改并提出一个PR
>
> Lab 1详细要求参见[WriteUp](Assignments/Lab1.md)，**截止日期：2022.09.28 11:59am**

## 第3次课：开源贡献指南（课堂lecture） 09/21   

* 301：开源参与概述：怎么参与开源项目和社区。     **lecture301**   

* 301：开源贡献指南：     **lecture302**
  - learn how the open source community works;    
  - criteria to select open source project and task to participate in.  

* 303: 以特定GitHub项目/任务为例，展示如何做贡献；以及讲述往年同学的贡献历程和体会。（消除畏惧感）  **lecture303**    

> **Lab 2：了解开源项目的开发方式和贡献流程（7分，两周）**
> 
> 任意选择一个活跃、成熟的开源项目：
> - 了解并报告CONTRIBUTING.md的形式和内容
> - 回答有关其贡献流程、质量管理方式等若干问题
>
> Lab 2详细要求参见[WriteUp](Assignments/Lab2.md)，**截止日期：2022.10.05 11:59am**

## 第4次课：开源项目maintainer分享其维护/开发的经验。（多个项目，开拓视野&为开源任务选择做准备）  	 09/28

 * 开源项目的分享：项目介绍、技术介绍、项目常用规则、如何参与。    
 
         * 张军（百度飞桨）：飞桨开源社区及开源贡献介绍
         * 林俊旸（阿里巴巴达摩院智能计算实验室）：多模态大模型开源介绍，以及达摩院一站式开源模型服务平台介绍
         * 齐宝玮（华为鸿蒙）：开源鸿蒙开发者社区运营经验分享

## 第5次课：开源开发的思想和原则；开源任务的实践和经验。（课堂lecture）  10/05   

* 501：从经典软工到开源开发  **lecture501**
* 502：如何选择开源任务参与，GitHub Good First Issue       **lecture502**

> **Lab 3：在开源项目中选择开发任务（8分，两周）** 
> 
> - 选择一个或者多个感兴趣的开源项目，探索并报告：
>   * 是否具有Good First Issue机制
>   * 如果你需要在其中选择开发任务，你会如何做
> 
> Lab 3详细要求参见[WriteUp](Assignments/Lab3.md)，**截止日期：2022.10.19 11:59am**

## 第6次课：（课程项目开题报告）选择开源项目和开源任务  10/12

* 学生报告，
         1）初始选择了什么开源项目和任务；
         2）对此开源项目及其指南的认识；
         3）贡献计划。

## 第7次课：CI/CD（上机实习）     10/19
 
> **Lab 4：CI/CD流水线搭建（10分，两周）** 
> 
> 了解CI/CD流程管理工具GitHub Action，知道如何编写简单的CI/CD流水线，并且在实践项目上完成符合要求的成功构建
>
> Lab 4详细要求参见[WriteUp](Assignments/Lab4.md)，**截止日期：2022.11.02 11:59am**
>
> 4Fun: 2021课程实习过程中关于gitee go的建议：https://toscode.gitee.com/pitcher/gitee-go-exercise/issues  

## 第8次课：开源社区及开源文化，与开源布道师面对面  
* 陈绪：漫谈云计算和开源社区
* 李建盛：多重维度下的开源之史
* 朱其罡：开放原子基金会及其开源项目简介
> (实际发生在11/16)

## 第9次课：PyPI/NPM等包生态系统/包管理工具，使用/打包/上载软件包（上机实习） 11/2

> **Lab 5：Python开源软件包安装/管理/打包/上载（10分，三周）**
>
> - 使用Poetry进行Python包的安装、管理与打包；
> - 利用依赖对Python包实现新功能；
> - 将自己的Python包手动发布到TestPyPI；
> - 配置自动化的CI/CD流水线实现从GitHub直接发布Python包到TestPyPI（注意，不是PyPI平台。[TestPyPI](https://test.pypi.org)是与PyPI分离的Python包发布平台，使练习时发布的Python包不会影响到真正的生态）
>
> Lab 5详细要求参见[WriteUp](Assignments/Lab5.md)，**截止日期：2022.11.23 11:59am**

## 第10次课：（课程项目进度报告）任务选择/合作反馈/工具使用等 PRJ-2    11/9


## 第11次课：开源开发中的沟通实践（课堂lecture）     

* 协作和沟通的重要性，如何沟通，分布式沟通中的要点，如何提交PR等。
> (实际发生在10/26)

> **Lab 6：开源项目中的沟通实践（8分，两周）**
>
> 阅读Linux Kernel沟通实践相关资料，体会总结开源沟通的最佳实践。
> or, 选择任何一个开源项目，阅读体会其沟通实践，总结最佳实践。
> （8分）
>
> - 提交issue时如何参与讨论，如何沟通
> - 提交pr时如何沟通
>
> Lab 6详细要求参见[WriteUp](Assignments/Lab6.md)，**截止日期：2022.12.07 11:59am**

## 第12次课：开源的几个关键问题：（课堂lecture）     11/23
* 开源为什么能成功？
* 开源模式会主宰未来吗？
* 什么是“卡脖子”问题？


## 第13次课：开源开发和生态相关的挑战和研究（课堂lecture） 11/30

* 开源数字社会学（数据驱动的开源研究，研究对象：软件~开发者，软件供应链~个体效率/群体协作/生态持续性）
* 发现型和发明型研究案例
         * 何昊：第三方库推荐，从三方库迁移的现象理解到智能推荐工具
         * 肖文鑫：新手任务推荐，从理解新手任务的性质到智能推荐工具


## 第14次课：开源商业模式（课堂lecture）   12/7  

* 公司为什么参与开源？
* 开源商业模式有哪些？
* 学生选择案例（特定公司和特定开源项目），说明其开源商业模式。

## 第15次课：课程项目结题报告 PRJ-3 12/14  

> 最后一次课之后需要提交课程项目最终报告（LaTeX格式），**截止日期：2022.12.28 11:59am**
>
> 课程项目的详细要求参见[WriteUp](Assignments/Project.md)

## 评分标准

* 课堂表现（10分）：  
    - 上课参与讨论、提问，若点名未到且未事先请假，一次扣2分，最多10分
    - 课堂表现优秀者，视情况酌情加分  
*	上机实习Lab（6个，共50分）：  
    - Git/贡献指南/GFI/沟通，7~8分一个，共30分  
    - CI/CD和包管理，10分一个，共20分  
*	课程项目PRJ（40分）：  
    - 3次presentation（开题/中期/结题），每次5分  
    - 期末报告10分  
    - 最后的贡献结果15分  
