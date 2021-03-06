# Crawlab

基于Golang的分布式爬虫管理平台，支持多种编程语言以及多种爬虫框架.

[查看演示 Demo](http://crawlab.cn/demo)

项目自今年三月份上线以来受到爬虫爱好者们和开发者们的好评，不少使用者还表示会用Crawlab搭建公司的爬虫平台。经过近数月的迭代，我们陆续上线了定时任务、数据分析、网站信息、可配置爬虫、自动提取字段、下载结果、上传爬虫等功能，将Crawlab打造得更加实用，更加全面，能够真正帮助用户解决爬虫管理困难的问题。

Crawlab主要解决的是大量爬虫管理困难的问题，例如需要监控上百个网站的参杂`scrapy`和`selenium`的项目不容易做到同时管理，而且命令行管理的成本非常高，还容易出错。Crawlab支持任何语言和任何框架，配合任务调度、任务监控，很容易做到对成规模的爬虫项目进行有效监控管理。

本使用手册是一个安装使用开发指南，帮助您安装、使用、开发 Crawlab。

如果您想尽快上手 Crawlab，请查看 [快速开始](./QuickStart/README.md)。

首先，我们来看如何安装Crawlab，请查看 [安装章节](./Installation/README.md)。关于如何使用，请查看 [使用章节](./Usage/README.md)。对于比较简单的爬虫，您可以使用 [可配置爬虫](./Usage/Spider/ConfigurableSpider.md)，比较节省时间；对于比较复杂的（例如需要登录）的爬虫，您可以使用 [自定义爬虫](./Usage/Spider/CustomizedSpider.md)，更加灵活。

⚠️**注意**: 如果您在安装过程中遇到任何问题，请查看 [Q&A](./QA/README.md) 来一一排查。如果仍然不能解决问题，请尝试到 [Github Issues](https://github.com/crawlab-team/crawlab/issues) 寻找解决办法。如果还是无法解决问题，请加作者微信 tikazyq1 并注明 "Crawlab"，作者将拉您入群，在群里您可以寻求大佬们的帮助。

