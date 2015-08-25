---
layout: docs
title: Feel++ People
permalink: /members/
---

{% for member in site.data.members %}
<p>
<table>
	<tr>
		<td height="70" width="70">
			<img src="https://github.com/{{ member.github }}.png" class="avatar-big" alt="{{member.name}}" width="64" height="64">
		</td>
		<td>
			<ul>
				<li> <a href="https://github.com/{{ member.github }}" class="post-author">{{ member.name }} </a> </li> 
				<li>{{ member.bio }}   </li> 
				<li>{{ member.place }} </li>
			</ul>
	</td></tr>
</table>
</p>
{% endfor %}
