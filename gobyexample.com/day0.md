
2018/04/08

数据结构:
	1.数组[Array]

	2.切片[Slices]
		
		2种声明方式
		1). 内置函数 make
			s := make([]int, 5)
		2). s := []string{"a", "b", "c"}

		其他操作
		copy, append 等

		more than Array

	3.映射[Map] key/value
		2 种声明方式

		1). 内资好函数make
			m := make(map[string]int)

		2). m := map[string]{"apple":2, "banner": 4}

	相关内置函数: len, copy delete append


迭代(Range interes)
	循环数组、切片、映射

	for k, v := range data-structure {

	}


函数
	初始函数(Function)
	多值返回函数(Multiple Function)
	可变参数函数(variadic Functions)

	匿名函数(closures) *
	递归函数(recursion)

其他概念; 空白标识符(blank identifier): _

下一节: 指针
