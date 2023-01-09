---
layout: single
title:  "Hexagonal architecture implementation"
excerpt: "How to implement hexagonal architecture in Java?"
date:   2023-01-08 11:52:31 +0100
categories: software design
---
The **hexagonal** (also known as **ports and adapters**) architecture is a trendy way to structure your application. 
The scope of the pattern is one service.
It describes a practical way to organize code for extensibility and testability.

# How does it look like?

![Folder structure](/assets/images/folders.png)

## Domain
This is the most important part of all applications. You put all the business logic and entities here. 

## Application
## Infrastructure

{% highlight java %}
@SpringBootApplication
public class BankingApplication {

    public static void main(String[] args) {
        SpringApplication.run(BankingApplication.class, args);
    }
}
{% endhighlight %}