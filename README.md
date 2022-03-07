 <center>
     <h1>个人简历</h1>
 </center>


## 个人信息 

* 性 别：男&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;年 龄：27  
* 手 机：13296614399 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;  邮 箱：2383492886@qq.com    
* 专 业：机械工程专业 &emsp;&emsp;&emsp;&emsp;&emsp; 岗 位：测试工程师

## 工作及教育经历

* 上海宾通智能科技有限公司&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;2019.04~至今&emsp;&emsp;&emsp;&emsp;&emsp; 机器人事业部-测试工程师  
* 武汉深海弈智科技有限公司&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;2017.10~2019.04&emsp;&emsp;&emsp;&emsp;&emsp; 研发部-结构工程师       
* 武汉大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2017.9~至今&emsp;&emsp;&emsp;&emsp; 机械工程-研究生         
* 河海大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2013.9~2017.7&emsp;&emsp;&emsp;&emsp; 能源与动力工程专业-本科  

## 专业技能

* 熟悉ubuntu系统操作，掌握ROS系统基本编程技巧
* 熟练使用 python，掌握C++，bash，了解javascript、groovy等编程语言
* 掌握基础数据结构和算法的基本原理
* 掌握自动化测试的基本技术

## 项目经历

1. 武汉深海弈智科技有限公司 - AGV本体结构设计 - 团队开发 - 201710- 201904
    * 设计并制造用于瓦楞纸厂及光伏产线的搬运AGV本体。
    
    * 光伏行业AGV使用麦克纳姆轮底盘结构及差动轮底盘结构，导航技术可选择自然激光导航及二维码导航。
    
      配合母公司光伏产线产线及上下料机器人在多家光伏工厂部署使用。
    
    * [公司产品官网](http://www.jsmachineai.com/)
    
    * 关键词：AGV, 机械设计
    
2. 上海宾通科技有限公司 - AGV方案仿真 - 独立开发 - 201912- 202101 

    * 通过客户厂区平面CAD图，涉及AGV运行路线，并在gazebo中进行AGV运行仿真。

    * 在CAD中设计AGV运行路线，并转化为公司调度软件可识别的路径信息倒入调度软件。提取厂区CAD图

      的墙体及货架轮廓生成DAE模型导入gazebo，在gazebo中模拟AGV运行，优化AGV路径及避障设计。

    * 客户现场持续运行，通过仿真对客户现场部署AGV的可行性进行了验证，并提前优化了运行路线，缩短了

      现场施工周期。

    * 示例效果：

    * 关键词：CAD, 3d-max, gazebo, semulation 

3. 上海宾通科技有限公司 - AGV自动化测试框架 - 独立开发 - 202103- 202109 

    * 搭建适用于AGV单机控制软件的自动化测试框架，将手动测试内容转化为自动化或人为协助的测试用例

    * 测试框架采用pytest+selenium，将产品web界面元素通过POM模型抽象整理，模拟需要人为操作的行为，

      涉及硬件操作需要人为介入时，浏览器弹窗提示并等待人为介入确认。

    * 该框架通过弹窗提示人为介入，几乎可以转化所有的手动测试用例，打打提高了测试准备和测试环节的效率。

    * 示例效果：

    * 关键词： pytest, selenium, allure, http, POM, javascript, jenkins

4. 上海宾通科技有限公司 - 精度自动采集工具 - 独立开发 - 202110- 202111

    * 利用Apriltag开源工具搭建的便携的AGV停车精度自动采集工具

    * 将测试模块安装在车体上，在需要测试精度的工位部署二维码。通过查询调度系统数据库获取车辆任务状态，

      自动将Apriltag感知后转换的机器人位姿记录到数据库，并通过pyplot显示测试结果。

    * 该工具开发过程优化了相机标定方法，冰采用合适的二维码部署方案，为AGV运行精度获取提供了可靠的

      反馈。

    * 示例效果：

    * 关键词：apriltag, ros, mysql, pyplot, camera

5. 上海宾通科技有限公司 - SLAM数据包回放工具 - 独立开发 - 202112- 202102

    * 采用jenkins+docker平台搭建的一款在线回放数据包的工具。

    * 手动触发jenkins平台的相应slam功能任务，上传数据包及现场参数后，在docker中回放数据包并运行slam产品。

      通过novnc将docker中运行界面转到web上方便进行分析，并打包录屏、运行结果至jenkins运行结果，方便

      下载运行结果。

    * 该工具后续进行通过jenkins-API编写单机客户端，自动录制并上传数据包触发回放任务，并将运行结果记录到数据
    
      库。通过开源的dataease工具，搭建了AGV运行状态看板。
    
    * 示例效果：
    
    * 关键词：jenkins, slam, docker, mysql, dataease

## 获奖经历
* XXX 优秀新人
* XXX 学生社团优秀干部
* 竞赛 XXX 奖

## 个人账号 
* github 地址 (附加自己github特色，突出的项目)

## 其他信息 
* 喜欢钻研新技术 等等
* 性格开朗，爱好：羽毛球、公路车、跑步
