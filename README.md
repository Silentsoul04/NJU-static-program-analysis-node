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
		- [Pointer Analysis 和 Alias Analysis 的区别](./8.Pointer-Analysis.md#head5)
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