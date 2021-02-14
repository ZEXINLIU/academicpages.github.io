---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
* Submitted
On the computation of recurrence coefficients for univariate orthogonal polynomials [arXiv](https://arxiv.org/abs/2101.11963)

* Preprint
<style>
table th:first-of-type {
    width: 60%;
}
table th:nth-of-type(2) {
    width: 20%;
}
table th:nth-of-type(3) {
    width: 20%;
}
</style>

| Title | Author | arXiv/PDF |
| On the computation of recurrence coefficients for univariate orthogonal polynomials| Zexin Liu Akil Narayan | [arXiv:2101.11963, 2021](https://arxiv.org/abs/2101.11963) |

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
