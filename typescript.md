函数类型

function fun1(a: number, b: number, c?: number): string {

​	return 'abc'

}

function fun1(a: number, b: number, c = number): string {

​	return 'abc'

}

function fun1(a: number, b: number, ...c: number[]): string {

​	return 'abc'

}

const func2: (a: number, b: number) => string = function (a: number, b: number): string{

​	return 'abc'

}

断言：

const num = res as number

const num = <number>res // JSX 下不能使用

接口：

interface Post {

​	subtitle? : string

​	readonly summary: string

}



```
interface Cache {

	[prop: string]: string

}
```

类：

class Person {

​	name: string

​	protected age: string

​	constructor(name: string) {

​		this.name = name

​		this.age = age

​	}

}

class Student extends Person {

​	constructor(name: string, age: string) {

​		super(name, age)	

​	}

}

类与接口：

interface EatAndRun {

​	eat (foot: string) : void

​	runt (distance: number) : void

}

class Person implements EatAndRun {

​	eat (food: string): void {

​	}

​	run (distance: number) {

​	}

}

class Person implements Eat, Run {

​	eat (food: string): void {

​	}

​	run (distance: number) {

​	}

}

泛型：用在函数，接口和类上面



类型声明：

import { camelCase } from 'lodash'

declare function camelCase (input: string): string

const res = camelCase('hhh')