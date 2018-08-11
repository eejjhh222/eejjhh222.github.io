---
layout: page 
title: board

---

# Some info 
...board how cool you are TT

<div class="page-content wc-container">
	<div class="post">
		<h1>board</h1>  
		<ul>
			{% for board in site.tags %}
			<li><a href="{{ '/boards/' | append:board[0] | relative_url }}">{{ board[0] }}</a></li>
			{% endfor %}
		</ul>
	</div>
</div>