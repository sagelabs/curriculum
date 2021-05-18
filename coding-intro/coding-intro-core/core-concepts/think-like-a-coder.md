---
author: abdullah

tags:
  - discussion

type: normal

category: discussion

---


# Think like a coder

---
## Content

Coding is all about saving time (and sometimes about making money 😉).

Let's look at a scenario.

Imagine you have to simulate grabbing 5 coins from 3 different jars. 

You could make a function, `pick_coins`, with 3 commands and use it 5 times, saving yourself a lot of time.

```python
pick_coins(){
#Grab coin 1
#Grab coin 2
#Grab coin 3
}

pick_coins()
pick_coins()
pick_coins()
pick_coins()
pick_coins()
```

Now imagine, you need to grab 100 coins from 80 jars. 

You could put `pick_coins` inside a loop; however, you still need to write 100 lines of code to grab each coin.

Maybe you could put a loop inside `pick_coins` to repeat the grab coin command 100 times; in that case, you'll still need to call the function `pick_coins` 80 times.

There has to be a better way! What else can we do?

Can we put a loop inside another loop? A [loop-de-loop](https://www.youtube.com/watch?v=Yhnx1q1_Bko&ab_channel=TheFabulousEchoes-Topic)? 
Could that solve our problem? 