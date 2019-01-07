---
layout: post
title: "[test] testtesttest"
subtitle: 'testtesttest.'
date: 2019-01-07
author: aiden
cover: '/images/cover.jpg'
tags: test web
comments: true
sitemap :
  changefreq : daily
  priority : 1.0
---

## Goal
> - test


**ex** <mark>test.</mark>

---

## test123
### ㄴsrc/main/java
: java source code
- class(Servlet)
    - controller package
    - service package
    - dao package
    - model package


### ㄴweb (webapp)
: static files, templates, xml, properties
- static or ~~resources~~ DIR
    - css, images, fonts, js..
- WEB-INF 
    - props or database DIR
        - jdbc.properties
    - views 
        - includes DIR
            - header / footer / layout
        - jsp or html 
    - web.xml
    - XXXconfig.xml
        - applicationContext.xml
        - dispatcher-servlet.xml
        - serviceContext.xml
        - daoContext.xml
        - securityContext.xml

### ㄴpom.xml
: Maven 
- Property

<mark>remark</mark>
* dispatcher-servlet.xml
    * `<mvc:resources mapping="/static/**" location="/static/" />`
    * web/static/
    * <span style="background-color: #e1e1e1">**/**</span>는 "web/" location

---
