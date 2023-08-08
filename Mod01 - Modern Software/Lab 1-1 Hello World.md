# Lab 1-1: Hello World
#### Introduction to Java
---
## Lab Objectives

This is a simple warm up lab to get you familiar with the using the Eclipse IDE in the supplied Virtual Machines. If you are already familiar with Eclipse, or are using your own IDE on your own machine, feel free to skip over this lab

---

## Part One: The Application

The following is the standard "Hello World" application required by law to be the first exercise done in any introductory programming class.

```java
public class HelloWorld {
    public static void main(String []args) {
        System.out.println("Hello World");
    }
}
```

If you are new to Java, then the code seem awkwardly verbose compared to other languages. Python, for example

```python
  print('Hello World')
```

But remember the discussion about how code is packaged in an OO language - every method or function must be defined within a class definition. 

The class HelloWord is just a container where you can put the one line of executable code to ensure that it actually gets executed.

Python, on the other hand, allows you to declare and use code without having to put it in any sort of container. Neither is right or wrong, Java and Python just represent two different philosophies and subsequent language design choices about how to write code.

In you are new to Java, done't worry about what all the code actually does, that will become more clear as we go through the course.

---
## Part Two: Using Eclipse

Power up and log into your VM like you did the the walk through. The Eclipse icon should be pinned to the task bar. If not, then just search for it among the apps.

Once you start Eclipse, it will ask you for a workspace and provide you with a default location which is probably the one used to test the installation before class.

You can choose whatever location you want for your workspace. One strategy is to create a working directory at the root of your C:, like `C:\mywork`, then create a new workspace for each module.

Starting a new workspace is shown below:


![Eclipse Workspace Selection](images/Lab1-0_Workspace.png?raw=true)

<img src="images/Lab1-0_Workspace.png?raw=true" width="80%" height="80%">


This is more text
