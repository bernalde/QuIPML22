---
title: Reading
layout: page
menuItem: Reading
menuPosition: 5
---
{% if site.docsUrl != "" %}
You can access all the required reading material via the links provided.
{% endif %}

From among many References, we will discuss in detail one or two papers (or book chapters) per class, depending on the topic. 
Students should read them in advance so that class discussions can be more productive.  

<!-- 1. [Integer programming classical methods](https://bernalde.github.io/QuIPML/syllabus/1-ip-basics.html) (Week 2)

2. [Ising, Quadratic Unconstrained Binary Optimization](https://bernalde.github.io/QuIPML/syllabus/2-ising-qubo.html) (Week 3)
3. [Graver Augmented Multiseed algorithm (GAMA)](https://bernalde.github.io/QuIPML/syllabus/3-gama.html) (Week 4)
4. [Quantum methods for solving Ising/QUBO](https://bernalde.github.io/QuIPML/syllabus/4-quantum.html) (Week 6)
5. [Specialized hardware methods for solving Ising/QUBO](https://bernalde.github.io/QuIPML/syllabus/5-special-hardware.html) (Week 4)
6. [Other topics and project presentations](https://bernalde.github.io/QuIPML/syllabus/6-others.html) (Week 7 and 14) -->

<ol>
{% assign syllabus = (site.syllabus | sort: "week") %}
{% for week in syllabus %}
  <li>
  	<a href="{{ site.baseurl }}{{ week.url }}">{{ week.title }}</a> 
  	{% for tag in week.tags %}
  		<b>#{{ tag }}</b>	
  	{% endfor %}
  	({{ week.day }})</li>
{% endfor %}
</ol>

Besides each week's papers there are some casual references we will visit. There is no single text book for the course. This is a  restricted list of various interesting and useful books that will be touched during the course. You may need to consult them occasionally.
- Georges Irfah, The Universal History of Computing, John Wiley & Sons, 2001.
- Eleanor G. Rieffel and Wolfgang H. Polak, Quantum Computing: A Gentle Introduction, MIT Press, 2011. [PDF](http://mmrc.amss.cas.cn/tlb/201702/W020170224608150244118.pdf)
- Richard J. Lipton and Kenneth W. Regan, Quantum Algorithms via Linear Algebra. A Primer, MIT Press, 2014.
