---
title: Home
---

# KlarText!

{% include figure.html img="uidaho-workshop.jpg" alt="intro image here" caption="Library workshop" width="75%" %}

KlarText workshop will explore a range of topics, from linguistic and computational approaches to simplification to readability assessment models, with a particular emphasis on the role of Large Language Models (LLMs) in generating and evaluating simplified text. Discussions will also cover the development of high-quality resources and benchmarks, human-centered evaluation techniques, and real-world applications such as assistive technologies and educational tools. Additionally, we will address cross-linguistic perspectives, examining how insights from German can inform multilingual and cross-lingual simplification efforts.


- **German Text Simplification:**  
  Methods for lexical, syntactic, and discourse-level simplification, including rule-based approaches, neural models, LLMs, and hybrid techniques. Evaluation frameworks for measuring simplification quality and linguistic fidelity.  

- **Readability Assessment:**  
  Computational readability metrics, corpus-based and machine-learning-driven models, and domain-specific readability considerations (e.g., medical, legal, and news texts).  

- **Resources & Approaches for *Leichte Sprache*:**  
  Parallel corpora with samples in *Leichte Sprache*, automated approaches to adhere to the rules in DIN SPEC 33429, participatory research projects including the target group.  

- **The Role of Large Language Models (LLMs):**  
  The risks and biases associated with LLM-driven simplification. Exploration of LLM applications in text simplification, readability prediction, and controlled text generation.  

- **Resources & Benchmarks:**  
  The creation and standardization of German-language datasets for simplification and readability assessment, including human-annotated corpora, automatic scoring methods, and domain-specific benchmarks.  

- **Evaluation & Human-Centered Assessment:**  
  Beyond automatic metrics (e.g., Flesch Reading Ease, perplexity), the workshop will explore human-centered evaluation strategies, incorporating usability studies, eye-tracking, and cognitive load assessment.  

- **Applications & Real-World Impact:**  
  Integration of simplification and readability models into NLP applications, such as assistive tools, automatic text adaptation for different reading levels, and AI-driven tutoring systems.  

- **Cross-Linguistic & Multilingual Perspectives:**  
  Comparisons between German and other languages, multilingual simplification models, and cross-lingual readability assessment approaches.  



<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [University of Idaho Library](http://www.lib.uidaho.edu/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
