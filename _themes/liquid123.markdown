---
title: Liquid123
date: 2015-10-31 20:03:00 -04:00
position: 2
---

{% highlight liquid %}
{% raw %}
{% if customer.name == "kevin" %}
  Hey Kevin!
{% elsif customer.name == "anonymous" %}
  Hey Anonymous!
{% else %}
  Hi Stranger!
{% endif %}
{% endraw %}
{% endhighlight %}