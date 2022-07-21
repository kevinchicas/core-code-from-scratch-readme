*<center> <h1>Interpreted vs Compiled Programming Languages </h1> </center>*



## **What's the Difference?**

When we need a source code converted in to a machine code before it can run, there are 2 ways to do this: 
 

**<center> 1. Compiled:**

Is when you have a source code and you use a compiler to convert it to machine code to be executed but can’t see the source code  

**2. Interpreted:**

 Is when it creates a copy of the source code and  interpreter program like a web browser reads line by line of the source code and interprets it 
 </center>
<br />

##  **What language should I use?**
---
More than choosing, we need to take in consideration the advantages and disadvantages of each. 


### **<center> 1. Compiled:**</center>

 **Advantages**  
<ul>
  <li>Faster execution</li>
  <li>Source code private</li>
</ul>



**Disadvantages**

<ul>
  <li>Additional time needed to complete the entire compilation step before testing </li>
  <li>Not cross-platform</li>
</ul>

### **<center>2. Interpreted:**</center>
**Advantages** 
<ul>
  <li>Tend to be more flexible, cross-platform</li>
  <li>Simpler to test</li>
</ul>

**Disadvantages**

<ul>
  <li>Source code is public </li>
  <li>Execution speed compared to compiled languages</li>
</ul>

</br>

## **Is Java compiled or interpreted, or both?**
---

Yes, a Java first compile into Bytecode which JRE can understand. ByteCode is then **interpreted** by the JVM making it as interpreted language too.

</br>

### **Exercise Pseudocode currency converter**
---

Paragraph:

User inputs amount  then system has to Save amount, then get price from (Bitcoin web database: coinbase, binance, crypto.com) then multiply amount with BTC price then show tota, warn the user ‘the price might change in the following 2 min’, reset after 2 mins. 

</br>

1-Start

2-User  <-- INPUT amount

3-Amount  <--  GET

4-BTC price <--  GET FROM (Bitcoin web database: coinbase, binance, crypto.com)

5-SHOW <--  Total  <-- WARN {Price might change in 2 mins and has to start over again}

6-IF 2 mins exceed <-- RESET

8-END

