# Gazelle支持基于iouring的高性能网络协议栈

**项目名称**： Gazelle支持基于iouring的高性能网络协议栈

**导师信息**: 
  - 姓名: 吴长冶
  - 邮箱: wuchangye@huawei.com

**难度**: 高

**分类**: 新型模块化组件 

**题目要求**

- 功能需求: 
  - 功能1:  Gazelle支持基于iouring收发数据，并开发适配层兼容posix api，做到业务免配套；（可优先对接tcp协议）
  - 功能2: Gazelle支持iouring模式，并支持该模式下网络收发的运维统计信息；
- 性能需求: 
  Gazelle基于iouring的高性能网络协议栈性能优于基于liburing改造的性能5%；
- 应用场景: 
  - 场景1：Redis
- 约束: 
  - 约束1: 基于 openEuler Gazelle项目做增强开发；
  - 约束2: 尽量做到业务无感、posix兼容；

**License**

- 许可协议: MulanPSL-2.0

**参考资料**

- 参考资料1: https://gitee.com/openeuler/gazelle
