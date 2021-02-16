### 🤔️ Introduces

this is part of the core knowledge points selected in the 11th `<ecamascript 2020>` edition of the ECMAScript language specification

这是从 ecmascript 11 版语言规范中节选出来的一些核心知识点

### Conformance

> 规范第二章节选

A conforming implementation of ECMAScript must provide and support all the types, values, objects, properties, functions, and program syntax and semantics described in this specification；

<font color="#cddcdf">符合 ECMAScript 规范的实现必须提供并支持本规范中描述的所有类型、值、对象、属性、函数以及程序语法和语义
</font>

A conforming implementation of ECMAScript must interpret source text input in conformance with the latest version of the Unicode Standard and ISO/IEC 10646

<font color="#cddcdf">符合 ECMAScript 规范的实现必须按照 Unicode 标准和 ISO/IEC 10646 的最新版本解释源文本输入
</font>

A conforming implementation of ECMAScript that provides an application programming interface (API) that supports programs that need to adapt to the linguistic and cultural conventions used by different human languages and countries must implement the interface defined by the most recent edition of `ECMA-402` that is compatible with this specification

<font color="#cddcdf">符合 ECMAScript 规范的实现，提供了一个应用程序编程接口(API) ，支持需要适应不同人类语言和国家使用的语言和文化约定的程序，必须实现最新版本的 `ECMA-402` 所定义的与本规范相兼容的接口</font>

### Overview

> 规范第三章 EcmaScript Overview 节选

ECMAScript is object-based: basic language and host facilities are provided by objects, and an ECMAScript program is a cluster of communicating objects. In ECMAScript, an object is a collection of zero or more properties each with attributes that determine how each property can be used—for example, when the `Writable` attribute for a property is set to false, any attempt by executed ECMAScript code to assign a different value to the property fails.

<font color="#cddcdf">符合 ECMAScript 是基于对象的: 基本语言和 host facilities `<主机设施>` 都是由对象提供的，一个 ecmascript 程序是一个通信对象的集群；在 ecmascript 中，对象是由 zero or more（0 个或多个）属性组成的集合，每个属性都是具有如何去使用他的属性；

举例：当 `Writable` 属性设置成了 `false`, 任何试图执行 ECMAScript code 去改成不同的值都会失败；

Properties are containers that hold other objects, primitive values, or functions.

<font color="#cddcdf">属性是容纳 `其他对像`、`原始值`、`functions`的容器；
</font>

A primitive value is a `member` of one of the following `built-in types`: Undefined, Null, Boolean, Number, BigInt, String, and Symbol;

an object is a member of the built-in type Object; and a function is a `callable` object. A function that is associated with an object via a property is called a method;

<font color="#cddcdf">
一个原始值是以下内置类型之一的成员,

-   Undefined,
-   Null,
-   Boolean,
-   Number,
-   BigInt,
-   String,
-   Symbol

对象是内置类型 Object 的成员，一个函数是一个 `可召回的`（可调用） 对象, 通过一个属性与对象关联的函数叫做方法
<font>

<font>
