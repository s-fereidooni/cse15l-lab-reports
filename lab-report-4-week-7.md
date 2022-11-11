# lab report week 4

## **Introduction**

In this lab we will be further exploring the use of vim and bash script in the modern world of computing. We will be exploring these uses in the scope of week 6, and viewing their uses in more applications. 


## **Part 1**

**Task from Week 6:** Changing the name of the start parameter and its uses to base

**Series of keys pressed:**
/start\<Enter>cgnbase\<Esc>n.n.n.

**Image of Sequence**

```
# find first instance of "start"
/start<Enter>
```
Output:
![](start.png)

```
# delete start and place cursor at start of word
# enter insert mode
# replace with "base"

cgnbase
```
Output:
![](cgnbase.png)

```
# return to normal mode
# find next instance of "start"

<Esc>n
```
Output:
![](escapen.png)

```
# replace with "base"

.
```
Output:
![](basereplace1.png)

```
# find next instance of "start" 

n.
```
Output:
![](basereplace3.png)


```
# replace with "base"

n.
```
Output:
![](replacewithbase4.png)

All under 30 keys pressed!


## **Part 2**
Timed Tasks:
- scp version
- vim version

**Completing the task with scp:**

*Time taken:* 4 minutes 30 seconds

![](fileinvs.png)

Open the file in VS Code

![](basereplacevs.png)

![](anotherbase.png)

Use ^F to find different instances of "start" and replace with "base".

Save the file and open terminal.

cd into skill-demo1

![](scpintoskilldemo.png)

run the base test file

![](scpbashtest.png)

**Completing the task with vim:**

*Time taken:* 1 minute

ssh into server
cd into skill-demo1
open file in vim with "vim DocSearchServer.java"
Make changes to the file with the command:

```
# key presses
/start\<Enter>cgnbase\<Esc>n.n.n.
```

![](start.png)

![](cgnbase.png)

![](escapen.png)

![](basereplace1.png)

![](basereplace3.png)

![](replacewithbase4.png)

Run the bash script

![](bashvim.png)

![](bashvim2.png)
