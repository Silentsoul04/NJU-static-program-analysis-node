# NJU-static-program-analysis-node

快速的过了一遍课程视频，大体了解了一下，打算看第二遍，并记下笔记。🙏感谢南大两位老师

[课程地址](https://pascal-group.bitbucket.io/teaching.html)

# 笔记目录

[1.Course Introduction](./1.Course-Introduction.md)

- [Course Introduction](./1.Course-Introduction.md#head1)
	- [PL and Static Analysis](./1.Course-Introduction.md#head2)
	- [Why We Lean Static Analysis](./1.Course-Introduction.md#head3)
	- [What is Static Analysis](./1.Course-Introduction.md#head4)
	- [Static Analysis Features and Examples](./1.Course-Introduction.md#head5)
		- [ soundness](./1.Course-Introduction.md#head6)
		- [ 如何实现](./1.Course-Introduction.md#head7)
		- [ 一个栗子](./1.Course-Introduction.md#head8)
		- [ 精度与速度平衡](./1.Course-Introduction.md#head9)
	- [Teaching Plan](./1.Course-Introduction.md#head10)
	- [Evalution Criteria](./1.Course-Introduction.md#head11)


[2.Intermediate-Representation.md](./2.Intermediate-Representation.md)

- [Intermediate Representation](./2.Intermediate-Representation.md#head1)
	- [Compilers and Static Analyzers](./2.Intermediate-Representation.md#head2)
	- [AST vs. IR](./2.Intermediate-Representation.md#head3)
	- [IR: Three-Address Code (3AC)](./2.Intermediate-Representation.md#head4)
	- [3AC in Real Static Analyzer : Soot](./2.Intermediate-Representation.md#head5)
	- [Static Single Assignment (SSA)](./2.Intermediate-Representation.md#head6)
	- [Basic Blocks (BB)](./2.Intermediate-Representation.md#head7)
	- [Control Flow Graphs (CFG)](./2.Intermediate-Representation.md#head8)

[3.Data-Flow-Analysis-I.md](./3.Data-Flow-Analysis-I.md)

- [Data Flow Analysis I](./3.Data-Flow-Analysis-I.md#head1)
	- [Overview of Data Flow Analysis](./3.Data-Flow-Analysis-I.md#head2)
	- [Preliminaries of Data Flow Analysis](./3.Data-Flow-Analysis-I.md#head3)
	- [Reaching Definitions Analysis](./3.Data-Flow-Analysis-I.md#head4)
		- [Reaching Definitions的定义](./3.Data-Flow-Analysis-I.md#head5)
		- [用bit vectors去表示是否可达](./3.Data-Flow-Analysis-I.md#head6)
		- [Transfer function and Control flow](./3.Data-Flow-Analysis-I.md#head7)
		- [ 算法](./3.Data-Flow-Analysis-I.md#head8)
		- [ 栗子](./3.Data-Flow-Analysis-I.md#head9)
		- [ 为什么会最终不变](./3.Data-Flow-Analysis-I.md#head10)

[4.Data-Flow-Analysis-II.md](./4.Data-Flow-Analysis-II.md)

- [Data Flow Analysis II](./4.Data-Flow-Analysis-II.md#head1)
	- [Live Variables Analysis](./4.Data-Flow-Analysis-II.md#head2)
		- [ 定义](./4.Data-Flow-Analysis-II.md#head3)
		- [transfer func and control flow merge](./4.Data-Flow-Analysis-II.md#head4)
		- [ 算法](./4.Data-Flow-Analysis-II.md#head5)
		- [ 栗子](./4.Data-Flow-Analysis-II.md#head6)
	- [Available Expressons Analysis](./4.Data-Flow-Analysis-II.md#head7)
		- [ 定义](./4.Data-Flow-Analysis-II.md#head8)
		- [transfer func and control flow merge](./4.Data-Flow-Analysis-II.md#head9)
		- [ 算法](./4.Data-Flow-Analysis-II.md#head10)
	- [ 三种算法对比](./4.Data-Flow-Analysis-II.md#head11)

[5.Data-Flow-Analysis-Foundations-I.md](./5.Data-Flow-Analysis-Foundations-I.md)

- [Data Flow Analysis - Foundations I](./5.Data-Flow-Analysis-Foundations-I.md#head1)
	- [Iterative Algorithm, Another View](./5.Data-Flow-Analysis-Foundations-I.md#head2)
	- [Partial Order](./5.Data-Flow-Analysis-Foundations-I.md#head3)
		- [ 偏序](./5.Data-Flow-Analysis-Foundations-I.md#head4)
	- [Upper and Lower Bounds](./5.Data-Flow-Analysis-Foundations-I.md#head5)
		- [ 定义](./5.Data-Flow-Analysis-Foundations-I.md#head6)
		- [ poset性质](./5.Data-Flow-Analysis-Foundations-I.md#head7)
	- [Lattice, Semilattce,Complete and Product Lattice](./5.Data-Flow-Analysis-Foundations-I.md#head8)
		- [ Lattice](./5.Data-Flow-Analysis-Foundations-I.md#head9)
		- [Complete Lattice](./5.Data-Flow-Analysis-Foundations-I.md#head10)
		- [Product Lattice](./5.Data-Flow-Analysis-Foundations-I.md#head11)
	- [Data Flow Analysis Framework Via Lattic](./5.Data-Flow-Analysis-Foundations-I.md#head12)
	- [Monotonicity and Fixed Point Theorem](./5.Data-Flow-Analysis-Foundations-I.md#head13)
		- [ 定义](./5.Data-Flow-Analysis-Foundations-I.md#head14)
		- [证明-Existence of fixed point](./5.Data-Flow-Analysis-Foundations-I.md#head15)
		- [证明-The fixed point is the least](./5.Data-Flow-Analysis-Foundations-I.md#head16)
		- [lattice 上数学运算与data analyse ](./5.Data-Flow-Analysis-Foundations-I.md#head17)

[6.Data-Flow-Analysis-Foundations-II.md](./6.Data-Flow-Analysis-Foundations-II.md)

- [Data Flow Analysis Foundations II](./6.Data-Flow-Analysis-Foundations-II.md#head1)
	- [Relate Iterative Algorithm to Fixed Point Theorem](./6.Data-Flow-Analysis-Foundations-II.md#head2)
		- [ 格与迭代算法对应](./6.Data-Flow-Analysis-Foundations-II.md#head3)
		- [ 证明迭代算法中F的monotonic](./6.Data-Flow-Analysis-Foundations-II.md#head4)
		- [ 什么时候到达fixed-point](./6.Data-Flow-Analysis-Foundations-II.md#head5)
	- [May/Must Analysis, A Lattice View](./6.Data-Flow-Analysis-Foundations-II.md#head6)
	- [Mop and Distributivity](./6.Data-Flow-Analysis-Foundations-II.md#head7)
		- [ mop定义](./6.Data-Flow-Analysis-Foundations-II.md#head8)
		- [ mop与迭代算法区别](./6.Data-Flow-Analysis-Foundations-II.md#head9)
	- [Constant Propagation](./6.Data-Flow-Analysis-Foundations-II.md#head10)
		- [非distributive的问题，must analysis](./6.Data-Flow-Analysis-Foundations-II.md#head11)
		- [ 问题映射到lattice上](./6.Data-Flow-Analysis-Foundations-II.md#head12)
	- [Worklist Algorithm](./6.Data-Flow-Analysis-Foundations-II.md#head13)

[7.Interprocedural-Analysis.md](./7.Interprocedural-Analysis.md)

- [Interprocedural Analysis](./7.Interprocedural-Analysis.md#head1)
	- [ Motivation](./7.Interprocedural-Analysis.md#head2)
		- [Call Graph](./7.Interprocedural-Analysis.md#head3)
	- [Call Graph Construction(CHA)](./7.Interprocedural-Analysis.md#head4)
		- [Call Graph算法对比](./7.Interprocedural-Analysis.md#head5)
		- [ Dispatch](./7.Interprocedural-Analysis.md#head6)
			- [Java中的method invoke](./7.Interprocedural-Analysis.md#head7)
			- [method signature](./7.Interprocedural-Analysis.md#head8)
			- [virtual call dispatch](./7.Interprocedural-Analysis.md#head9)
		- [ CHA](./7.Interprocedural-Analysis.md#head10)
			- [ 定义](./7.Interprocedural-Analysis.md#head11)
			- [ Resolve](./7.Interprocedural-Analysis.md#head12)
			- [ 全程序算法](./7.Interprocedural-Analysis.md#head13)
	- [Interprocedural Control-Flow Graph](./7.Interprocedural-Analysis.md#head14)
		- [ 定义](./7.Interprocedural-Analysis.md#head15)
	- [Interprocedural Data-Flow Analysis](./7.Interprocedural-Analysis.md#head16)
		- [ 过程间分析组成](./7.Interprocedural-Analysis.md#head17)
		- [Interprocedural Constant Propagation](./7.Interprocedural-Analysis.md#head18)
			- [ 组成](./7.Interprocedural-Analysis.md#head19)
			- [ 栗子](./7.Interprocedural-Analysis.md#head20)

[8.Pointer-Analysis.md](./8.Pointer-Analysis.md)

- [Pointer Analysis](./8.Pointer-Analysis.md#head1)
	- [ Motivation](./8.Pointer-Analysis.md#head2)
	- [Introduction to Pointer Analysis](./8.Pointer-Analysis.md#head3)
		- [Pointer Analysis 简述](./8.Pointer-Analysis.md#head4)
		- [/Pointer Analysis 和 Alias Analysis 的区别](./8.Pointer-Analysis.md#head5)
		- [ 指针分析在静态分析地位](./8.Pointer-Analysis.md#head6)
	- [Key Factors of Pointer Analysis](./8.Pointer-Analysis.md#head7)
		- [Pointer Analysis的四个取舍要素](./8.Pointer-Analysis.md#head8)
		- [Heap Abstraction](./8.Pointer-Analysis.md#head9)
			- [ 为什么堆抽象](./8.Pointer-Analysis.md#head10)
			- [Allocation-Site Abstraction](./8.Pointer-Analysis.md#head11)
		- [Context Sensitivity](./8.Pointer-Analysis.md#head12)
		- [Flow Sensitivity](./8.Pointer-Analysis.md#head13)
		- [Analysis Scope](./8.Pointer-Analysis.md#head14)
		- [ 课程涉及的特性](./8.Pointer-Analysis.md#head15)
	- [Concerned Statements](./8.Pointer-Analysis.md#head16)
		- [Pointer Analysis面向的指针类型](./8.Pointer-Analysis.md#head17)
		- [ Pointer Analysis面向的语句](./8.Pointer-Analysis.md#head18)

[9.Pointer-Analysis-Foundations-I.md](./9.Pointer-Analysis-Foundations-I.md)

- [Pointer Analysis - Foundations I](./9.Pointer-Analysis-Foundations-I.md#head1)
	- [Pointer Analysis:Rules](./9.Pointer-Analysis-Foundations-I.md#head2)
		- [ 影响指针的statements](./9.Pointer-Analysis-Foundations-I.md#head3)
		- [Domains and Notations](./9.Pointer-Analysis-Foundations-I.md#head4)
		- [ Rule](./9.Pointer-Analysis-Foundations-I.md#head5)
	- [How to implement Pointer Analysis](./9.Pointer-Analysis-Foundations-I.md#head6)
		- [ PFG](./9.Pointer-Analysis-Foundations-I.md#head7)
		- [实现Pointer Analysis](./9.Pointer-Analysis-Foundations-I.md#head8)
	- [Pointer Analysis:Algorithms](./9.Pointer-Analysis-Foundations-I.md#head9)

[10.Pointer-Analysis-Foundations-II.md](./10.Pointer-Analysis-Foundations-II.md)

- [Pointer Analysis with Method Calls](./10.Pointer-Analysis-Foundations-II.md#head1)
	- [call rule](./10.Pointer-Analysis-Foundations-II.md#head2)
	- [ 不加x到this](./10.Pointer-Analysis-Foundations-II.md#head3)
	- [Interprocedure Pointer Anaylsis Algorithm](./10.Pointer-Analysis-Foundations-II.md#head4)

[11.Pointer-Analysis-Context-Sensitivity-I.md](./11.Pointer-Analysis-Context-Sensitivity-I.md)

- [Pointer Analysis Context Sensitivity](./11.Pointer-Analysis-Context-Sensitivity-I.md#head1)
	- [ Introduction](./11.Pointer-Analysis-Context-Sensitivity-I.md#head2)
		- [Why Context Sensitivity](./11.Pointer-Analysis-Context-Sensitivity-I.md#head3)
		- [Cloning-Based Context Sensitivity](./11.Pointer-Analysis-Context-Sensitivity-I.md#head4)
		- [Why  Context-Sensitive Heap](./11.Pointer-Analysis-Context-Sensitivity-I.md#head5)
		- [Context-Sensitive Heap](./11.Pointer-Analysis-Context-Sensitivity-I.md#head6)
	- [Context Sensitive Pointer Analysis:Rules](./11.Pointer-Analysis-Context-Sensitivity-I.md#head7)
		- [Domains and Notations](./11.Pointer-Analysis-Context-Sensitivity-I.md#head8)
	- [ Rules](./11.Pointer-Analysis-Context-Sensitivity-I.md#head9)

[12.Pointer Analysis Context Sensitivity II](./12.Pointer-Analysis-Context-Sensitivity-II.md#head1)
	
- [Context Sensitive Pointer Analysis : Algorithms](./12.Pointer-Analysis-Context-Sensitivity-II.md#head2)
	- [ 定义](./12.Pointer-Analysis-Context-Sensitivity-II.md#head3)
	- [ algorithms](./12.Pointer-Analysis-Context-Sensitivity-II.md#head4)
- [Context Sensitivity Variants](./12.Pointer-Analysis-Context-Sensitivity-II.md#head5)
	- [Call-Site Sensitivity](./12.Pointer-Analysis-Context-Sensitivity-II.md#head6)
		- [ 栗子](./12.Pointer-Analysis-Context-Sensitivity-II.md#head7)
	- [Object Sensitivity](./12.Pointer-Analysis-Context-Sensitivity-II.md#head8)
		- [ 栗子](./12.Pointer-Analysis-Context-Sensitivity-II.md#head9)
	- [Type Sensitivity](./12.Pointer-Analysis-Context-Sensitivity-II.md#head10)
	- [ 对比](./12.Pointer-Analysis-Context-Sensitivity-II.md#head11)

[13.Static Analysis for Security](./13.Static-Analysis-For-Security.md#head1)

- [Information Flow Security](./13.Static-Analysis-For-Security.md#head2)
	- [Access Control vs. Information Flow Security](./13.Static-Analysis-For-Security.md#head3)
	- [Security Levels](./13.Static-Analysis-For-Security.md#head4)
	- [Information Flow Policy](./13.Static-Analysis-For-Security.md#head5)
- [Confidentiality and Integrity](./13.Static-Analysis-For-Security.md#head6)
	- [Confidentiality vs. Integrity](./13.Static-Analysis-For-Security.md#head7)
	- [Integrity, Broad Definition](./13.Static-Analysis-For-Security.md#head8)
- [Explicit Flows and Covert Channels](./13.Static-Analysis-For-Security.md#head9)
	- [Implicit Flow](./13.Static-Analysis-For-Security.md#head10)
	- [Covert Channels](./13.Static-Analysis-For-Security.md#head11)
- [Taint Analysis](./13.Static-Analysis-For-Security.md#head12)
	- [ 定义](./13.Static-Analysis-For-Security.md#head13)
	- [ 解决confidentiality、Integrity](./13.Static-Analysis-For-Security.md#head14)
	- [Taint 与Pointer Analysis结合](./13.Static-Analysis-For-Security.md#head15)
	- [Domains and Notations](./13.Static-Analysis-For-Security.md#head16)
	- [Taint Analysis Input & Output](./13.Static-Analysis-For-Security.md#head17)
	- [Taint analysis:rule](./13.Static-Analysis-For-Security.md#head18)
- [ 其他](./13.Static-Analysis-For-Security.md#head19)