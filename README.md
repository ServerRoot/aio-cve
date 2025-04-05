# aio-cve
Vulnerable Code Snippet: 

![](https://cdn.nlark.com/yuque/0/2025/png/12530259/1743515506621-979cff16-9ec4-4ce8-880d-55226e011776.png)

 The pickle module reconstructs objects by executing the **reduce** method of serialized classes. Attackers can craft a payload to execute arbitrary code during deserialization.No validation of the input file’s integrity or source. Attacker-controlled file path or If the application fetches cookies from a network source without validation. First, create a Python file called calc, execute the code in the diagram to generate a malicious serialization file 

![](https://cdn.nlark.com/yuque/0/2025/png/12530259/1743515506685-973e7aa1-1c05-4e8b-8476-39474f3fa2f0.png)

 Create a python file named Exploit in the malicious serialization file directory and run it to trigger the deserialization execution calc 

![](https://cdn.nlark.com/yuque/0/2025/png/12530259/1743515506717-186c29a1-3954-40d1-b798-bf278b882dfd.png)
