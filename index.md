---
layout: page
---

# Reproducible Science is good. Replicated Science is better.

Re**Science** is an open-access peer-reviewed journal that targets
computational research and encourages the explicit [replication](faq) of
already published research, promoting new and open-source implementations in
order to ensure that the original research is [reproducible](faq).

To achieve this goal, the whole publishing chain is radically different from
other traditional scientific journals. Re**Science** lives on
[GitHub](https://github.com/ReScience/) where each new implementation of a
computational study is made available together with comments, explanations and
tests. Each submission takes the form of a pull request that is publicly
reviewed and tested in order to guarantee that any researcher can re-use it. If
you ever replicated computational results from the literature in your research,
Re**Science** is the perfect place to publish your new implementation.

Re**Science** is collaborative and open by design. Everything can be forked and
modified. Don't hesitate to [write a submission](write), [join us](faq) and
to [become a reviewer](https://github.com/ReScience/ReScience/issues/27).

<br/>


# Latest publications

{% bibliography --max 3 --sort %}
<br>

# Latest News
<ul class="post-list">
  {% for post in site.posts limit:1 %}
  {% if post.type == "news" %}
  <li>
    <h4>{{ post.title }}
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span></h4>
    {{ post.content }}
  </li>
  {% endif %}
  {% endfor %}
</ul>

