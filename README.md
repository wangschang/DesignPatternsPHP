# DesignPatternsPHP
# php设计模式（基于php7）
[![Build Status](https://github.com/domnikl/DesignPatternsPHP/workflows/CI/badge.svg)](https://github.com/domnikl/DesignPatternsPHP/actions)
[![Documentation Status](https://readthedocs.org/projects/designpatternsphp/badge/?version=latest)](https://readthedocs.org/projects/designpatternsphp/?badge=latest)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/DominikLiebler)

[Read the Docs of DesignPatternsPHP](http://designpatternsphp.readthedocs.org)
or [Download as PDF/Epub](https://readthedocs.org/projects/designpatternsphp/downloads/)

This is a collection of known design patterns and some sample code how to implement them in PHP. Every pattern has a small list of examples.

这是一个php实现的设计模式的汇总，每个设计模式都有一个小栗子。
I think the problem with patterns is that often people do know them but don't know when to apply which.

我想关于设计模式的问题是：我们知道他但是不知道如何应用它们
## Installation

## 安装
You should look at and run the tests to see what happens in the example.

你应该看一下并允许测试看看例子是如何运行的

To do this, you should install dependencies with `Composer` first:

首先你要安装 Composer 的依赖

```bash
$ composer install
```

Read more about how to install and use `Composer` on your local machine [here](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx).

关于更多如何使`Composer`请阅读更多 [here](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx).

To run the tests use `phpunit`:

```bash
$ ./vendor/bin/phpunit
```

## using Docker (optional)

## 使用 Docker（可选）

You can optionally build and browse the documentation using [Docker for Mac, Windows or Linux](https://docs.docker.com/compose/install/).

查看相应文档请查看：[Docker for Mac, Windows or Linux](https://docs.docker.com/compose/install/).

Just run:

运行：

```bash
$ docker-compose up --build
```

Go to [http://localhost:8080/README.html](http://localhost:8080/README.html) to read the generated documentation.

在 [http://localhost:8080/README.html](http://localhost:8080/README.html) 查看生成文档。

## Patterns

## 设计模式

The patterns can be structured in roughly three different categories. Please click on the [:notebook:](http://en.wikipedia.org/wiki/Software_design_pattern) for a full explanation of the pattern on Wikipedia.

设计模式大概有三个目录组成，点击链接查看详细的Wikipedia 解释 [:notebook:](http://en.wikipedia.org/wiki/Software_design_pattern)

### [创建型模式](Creational)

* [抽象工厂模式](Creational/AbstractFactory) [:notebook:](http://en.wikipedia.org/wiki/Abstract_factory_pattern)
* [生成器模式](Creational/Builder) [:notebook:](http://en.wikipedia.org/wiki/Builder_pattern)
* [工厂方法](Creational/FactoryMethod) [:notebook:](http://en.wikipedia.org/wiki/Factory_method_pattern)
* [对象池](Creational/Pool) [:notebook:](http://en.wikipedia.org/wiki/Object_pool_pattern)
* [原型模式](Creational/Prototype) [:notebook:](http://en.wikipedia.org/wiki/Prototype_pattern)
* [简单工厂模式](Creational/SimpleFactory)
* [单例模式](Creational/Singleton) [:notebook:](http://en.wikipedia.org/wiki/Singleton_pattern) (is considered an anti-pattern! :no_entry:)
* [静态工厂](Creational/StaticFactory)

### [结构性设计模式](Structural)

* [Adapter](Structural/Adapter) [:notebook:](http://en.wikipedia.org/wiki/Adapter_pattern)
* [Bridge](Structural/Bridge) [:notebook:](http://en.wikipedia.org/wiki/Bridge_pattern)
* [Composite](Structural/Composite) [:notebook:](http://en.wikipedia.org/wiki/Composite_pattern)
* [DataMapper](Structural/DataMapper) [:notebook:](http://en.wikipedia.org/wiki/Data_mapper_pattern)
* [Decorator](Structural/Decorator) [:notebook:](http://en.wikipedia.org/wiki/Decorator_pattern)
* [DependencyInjection](Structural/DependencyInjection) [:notebook:](http://en.wikipedia.org/wiki/Dependency_injection)
* [Facade](Structural/Facade) [:notebook:](http://en.wikipedia.org/wiki/Facade_pattern)
* [FluentInterface](Structural/FluentInterface) [:notebook:](http://en.wikipedia.org/wiki/Fluent_interface)
* [Flyweight](Structural/Flyweight) [:notebook:](https://en.wikipedia.org/wiki/Flyweight_pattern)
* [Proxy](Structural/Proxy) [:notebook:](http://en.wikipedia.org/wiki/Proxy_pattern)
* [Registry](Structural/Registry) [:notebook:](http://en.wikipedia.org/wiki/Service_locator_pattern)

### [Behavioral](Behavioral)

* [ChainOfResponsibilities](Behavioral/ChainOfResponsibilities) [:notebook:](http://en.wikipedia.org/wiki/Chain_of_responsibility_pattern)
* [Command](Behavioral/Command) [:notebook:](http://en.wikipedia.org/wiki/Command_pattern)
* [Iterator](Behavioral/Iterator) [:notebook:](http://en.wikipedia.org/wiki/Iterator_pattern)
* [Mediator](Behavioral/Mediator) [:notebook:](http://en.wikipedia.org/wiki/Mediator_pattern)
* [Memento](Behavioral/Memento) [:notebook:](http://en.wikipedia.org/wiki/Memento_pattern)
* [NullObject](Behavioral/NullObject) [:notebook:](http://en.wikipedia.org/wiki/Null_Object_pattern)
* [Observer](Behavioral/Observer) [:notebook:](http://en.wikipedia.org/wiki/Observer_pattern)
* [Specification](Behavioral/Specification) [:notebook:](http://en.wikipedia.org/wiki/Specification_pattern)
* [State](Behavioral/State) [:notebook:](http://en.wikipedia.org/wiki/State_pattern)
* [Strategy](Behavioral/Strategy) [:notebook:](http://en.wikipedia.org/wiki/Strategy_pattern)
* [TemplateMethod](Behavioral/TemplateMethod) [:notebook:](http://en.wikipedia.org/wiki/Template_method_pattern)
* [Visitor](Behavioral/Visitor) [:notebook:](http://en.wikipedia.org/wiki/Visitor_pattern)

### [More](More)

* [EAV](More/EAV) [:notebook:](https://en.wikipedia.org/wiki/Entity%E2%80%93attribute%E2%80%93value_model)
* [Repository](More/Repository)
* [ServiceLocator](More/ServiceLocator) [:notebook:](http://en.wikipedia.org/wiki/Service_locator_pattern) (is considered an anti-pattern! :no_entry:)

参考地址 : https://designpatternsphp.readthedocs.io/zh_CN/latest/README.html

