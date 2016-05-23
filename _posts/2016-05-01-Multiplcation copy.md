---
layout: post
title: Multiplication of 2 numbers
---

Back in the 90's when I was a kid I clocked 0.05sec for multiplying two numbers for which I won the national award. I was faster than the so called powerful computers at that time;). I still hold the record for the same. People say that these days computers are much powerful and can do computations trillion times faster than us. So I decided to challenge these "Mighty" computers. This is the battle that has waited for decades. Many maestros are predicting that this is the battle of the century.

> Challenge the "Mighty" computers

Lets set the competation rules right.

{% highlight text %}
result = a * b
Given the "result" and "a" , Find "b".

For example:
result=20
a=5
b=?
{% endhighlight %}

I know that the computers are smart. Unfortunately we are not supposed to use addition/division to solve this.

>Note: Addition/Substraction/Division cannot be used.
example: 
   b= result/a; is not allowed

How can a computer solve this? It is not supposed to do repititive addition or division to find out the answer.A friend of mine is a decent programmer. He is gonna make the computer solve this.

TADA!!!! Computers are fast in doing a particular operation. So my friend decided to use the random number generatin method to solve this.

Repeatedly generate random numbers to find out for what value of "b" the result is 20.

{% highlight text %}
begin
a=5
repeat untill result=20
    b=random()
    result=a*b;
    if result == 20 
    print "BRAVO"
        break;
end
{% endhighlight %}

>I beat the computer hands down!!

My friend is not happy with the results. He is not gonna give up


