+++
date = '2025-05-12T15:50:38+08:00'
draft = false
title = 'My First Post'
math = true
categories = ['Main Sections']
tags = ['sample', 'C#']
+++

你好！

$$\boldsymbol{x}_{i+1}+\boldsymbol{x}_{i+2}=\boldsymbol{x}_{i+3}$$

```C# {name="Program.cs"}
private void Test()
{
    var processorCount = Environment.ProcessorCount;
        Parallel.For(0, processorCount, new ParallelOptions { MaxDegreeOfParallelism = processorCount },
            _ => IntensiveInt64Calculation());
}
```

![img](/img.png)