<!-- ---
layout: home
parent: common_library
grand_parent: Framework
nav_order: 3
has_children: false
has_toc: false
title: beta_equation
--- -->

<!--Don't delete ths script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete ths script-->

<h3>beta_equation</h3>
<p align = "justify">
    This function calculates the reliability index value for a given probability of failure (pf).
</p>

```python
beta_value = beta_equation(pf)
```

Input variables
{: .label .label-yellow }

<table style = "width:100%">
    <thead>
      <tr>
        <th>Name</th>
        <th>Description</th>
        <th>Type</th>
      </tr>
    </thead>
    <tr>
        <td><code>pf</code></td>
        <td>Probability of failure</td>
        <td>Float or String</td>
    </tr>
</table>

Output variables
{: .label .label-yellow }

<table style = "width:100%">
   <thead>
     <tr>
       <th>Name</th>
       <th>Description</th>
       <th>Type</th>
     </tr>
   </thead>
   <tr>
       <td><code>beta_value</code></td>
       <td>Beta value</td>
       <td>Float</td>
   </tr>
</table>

Example 1
{: .label .label-blue }

<p align = "justify">
    <i>Use <code>beta_equation</code> function to calculate the reliability index for a probability of failure of 2.32629e-04.</i>
</p>

```python
from parepy_toolbox import beta_equation

pf = 2.32629e-04
beta = beta_equation(pf)
print(f"Reliability index {beta:.2f}")
``` 

<p align = "justify">
    <i>Output details.</i>
</p>

```bash
Reliability index 3.50
``` 

{: .important }
> Incipient instability can be observed around $$\beta = 7.5$$, which increases significantly for $$\beta > 8$$.
