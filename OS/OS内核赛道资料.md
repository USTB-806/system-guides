## OS 内核赛道资料

### 操作系统入门：

jyy 老师的课门槛不高，非常推荐，可以在吃饭或者写代码时当 bgm，也非常推荐认真的花时间跟着学一遍，跟着敲一敲课上的代码。jyy 老师的课可以让你对于操作系统有一定的比较全面的认识

南京大学操作系统课程 蒋炎岩老师：[绿导师原谅你了的个人空间-绿导师原谅你了个人主页-哔哩哔哩视频 (bilibili.com)](https://space.bilibili.com/202224425?spm_id_from=333.337.0.0)

### Rust 教程
 
Rust 在 sys 领域的应用越来越多，清华的操作系统实验（rcore）也已经选用了 Rust，在系统能力大赛的内核赛道中更是大多数队伍使用 Rust 实现。对于操作系统感兴趣，想进一步参加比赛，探索操作系统方向的，Rust 非常值得你学习。

[Rust语言圣经(Rust Course)](https://course.rs/about-book.html)
[Rust 语言实战](https://github.com/sunface/rust-by-practice)
[Rust速查表（cheatsheet）](https://cheats.rs/) 该项目不仅提供了基础的语法速查，还有执行顺序详解和编写时需要关注的注意事项。项目还包含了示例代码（EX）、书籍（BK）、标准（STD）等相关资料的扩展。

### 实战和比赛前置

只是听课当然不足以让你有能力参加系统能力大赛，你需要一系列前置的实验和学习，以下是一些很好的参考：

（如果你是北科的同学，正在修读操作系统这门课，可以视情况和你的老师/助教商量，使用以下的某个实验代替本校的操作系统实验）


#### rCore
清华的操作系统实验，目前国内最优秀的操作系统实验之一，建议通过 **rCore-Tutorial-Book** 进行理论学习，通过 **rCore-Tutorial-Guide-2024S** 进行实践。独立完成 rCore 之后，相信你就会有能力参与系统能力大赛，并获得不错的奖项。注意，学习 rCore 需要你前置的学习 Rust。

如果你选择 rCore，我非常推荐你参加[清华开源操作系统夏令营](https://opencamp.cn/os2edu/camp/2025spring)，训练营包含了从 Rust 到 rCore 的全流程教程和测评机，时间上**与系统能力大赛并不冲突**，且顺利结营可以有机会获得到清华的实习机会。

[rCore-Tutorial-Book 第三版](https://rcore-os.cn/rCore-Tutorial-Book-v3/chapter0/index.html) 
[rCore-Tutorial-Guide-2024S 文档 (learningos.cn)](https://learningos.cn/rCore-Tutorial-Guide-2024S/)

#### jyyos

南京大学蒋炎岩老师的操作系统课程配套实验，非常优秀，蒋炎岩老师的课也是编写文档的两位同学投入系统方向的原因。

https://jyywiki.cn/OS/2025/

jyy 老师的课在 2025 年改版，配套实验只剩下了更加偏向于考察系统编程能力（个人见解）的 M 编程实验，希望做系统实验 L 的同学可以看往期的课程。

#### MIT xv6

经典的 OS 优秀本科生实验，被北大选用，这里引用 [csdiy](https://csdiy.wiki) 的链接:

https://csdiy.wiki/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/MIT6.S081/

### risc-v 体系结构

系统能力大赛分为 RISCV 和 LoongArch 两个赛道（2025年开始，初赛要求同时支持两个架构），对于 RISCV 的深入理解在编写操作系统的时候极其重要，下面是一些资料。

**RISC-V手册（绝对的，没有理由的，必看）**： 
[riscv-privileged.pdf](riscv-privileged.pdf)  
[riscv-unprivileged.pdf](riscv-unprivileged.pdf) 
**记住，RTFM**

linux for RISCV 内核内存布局：[RISC-V Linux上的虚拟内存布局 — The Linux Kernel documentation](https://www.kernel.org/doc/html/v6.8/translations/zh_CN/arch/riscv/vm-layout.html)
Linux 的文档，动手写的时候会很有用。

以下内容均为选学，因为我也没有全部看过

- （Option）自学[PPT for RISC-V特权指令级架构](https://content.riscv.org/wp-content/uploads/2018/05/riscv-privileged-BCN.v7-2.pdf)
- （Option）自学[RISC-V手册：一本开源指令集的指南](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf) 重点是第10章
- （Option）自学[RISC-V特权指令级规范](https://riscv.org/technical/specifications/) 重点是与OS相关的特权硬件访问的规范内容（Privileged Spec）
- （Option）自学[RISC-V汇编手册](https://github.com/riscv-non-isa/riscv-asm-manual/blob/master/riscv-asm.md)
- （Option）[计算机组成与设计：RISC-V 教材](https://item.jd.com/12887758.html) 这是完整的课程教材，不要求全部看完，请根据自己的需求选择。
- （Option）[计算机组成与设计：RISC-V 浙大在线课程](http://www.icourse163.org/course/ZJU-1452997167) 这是完整的一门课，不要求全部看完，请根据自己的需求选择。

### ArceOS Tutorial book:
组件化操作系统的一种尝试，可以了解一下

[ArceOS 框架设计 - ArceOS Tutorial Book (rcore-os.cn)](https://rcore-os.cn/arceos-tutorial-book/ch02-02.html)

ArceOS 的文档目前还没有写完，可以参考一下。

### 系统能力大赛

系统能力大赛官网：[全国大学生计算机系统能力大赛 (educg.net)](https://os.educg.net/#/)

### 2024初赛样例：

[oscomp/testsuits-for-oskernel at main (github.com)](https://github.com/oscomp/testsuits-for-oskernel/tree/main?tab=readme-ov-file)

### 2024初赛赛题：

[testsuits-for-oskernel/oscomp_syscalls.md at main · oscomp/testsuits-for-oskernel (github.com)](https://github.com/oscomp/testsuits-for-oskernel/blob/main/oscomp_syscalls.md)

### 往届作品：

比赛允许借鉴，借鉴其他的优秀设计是开发 kernel 的重要一环。
当然，不能全抄

| 队名          | **学校**           | **仓库链接**       |
| -------------------- | -------------------------- | ------------------------------------------------------------ |
| **PLNTRY**           | **西安交通大学**           | **https://gitlab.eduxiji.net/PLNTRY/OSKernel2023-umi**       |
| **Main.os(2)(1)(1)** | **北京科技大学**           | **https://gitlab.eduxiji.net/202310008101520/oskernel2023-x** |
| **你说对不队**       | **河南科技大学**           | **https://gitlab.eduxiji.net/202310464101015/oskernel2023-byteos** |
| **Alien**            | **北京理工大学**           | **https://gitlab.eduxiji.net/202310007101563/Alien**         |
| **种田队**           | **北京航空航天大学**       | **https://gitlab.eduxiji.net/202310006101080/zhongtianos**   |
| **Titanix**          | **哈尔滨工业大学（深圳）** | **https://gitlab.eduxiji.net/202318123101314/oskernel2023-Titanix** |

