---
title: CommonLit Readability Prize
subtitle: A Kaggle challenge
image: /assets/img/portfolio/readability.png
alt: Books on a shelf

caption:
  title: CommonLit Readability Prize
  subtitle: A Kaggle challenge
  thumbnail: /assets/img/portfolio/readability.png
---
From the competition description:

<blockquote cite="https://www.kaggle.com/c/commonlitreadabilityprize" style="background: lightgrey;">
Can machine learning identify the appropriate reading level of a passage of text, and help inspire learning? Reading is an essential skill for academic success. When students have access to engaging passages offering the right level of challenge, they naturally develop reading skills.
<br>
<br>

Currently, most educational texts are matched to readers using traditional readability methods or commercially available formulas. However, each has its issues. Tools like Flesch-Kincaid Grade Level are based on weak proxies of text decoding (i.e., characters or syllables per word) and syntactic complexity (i.e., number or words per sentence). As a result, they lack construct and theoretical validity. At the same time, commercially available formulas, such as Lexile, can be cost-prohibitive, lack suitable validation studies, and suffer from transparency issues when the formula's features aren't publicly available.
<br>
<br>

CommonLit, Inc., is a nonprofit education technology organization serving over 20 million teachers and students with free digital reading and writing lessons for grades 3-12. Together with Georgia State University, an R1 public research university in Atlanta, they are challenging Kagglers to improve readability rating methods.
<br>
<br>

In this competition, you’ll build algorithms to rate the complexity of reading passages for grade 3-12 classroom use. To accomplish this, you'll pair your machine learning skills with a dataset that includes readers from a wide variety of age groups and a large collection of texts taken from various domains. Winning models will be sure to incorporate text cohesion and semantics.
<br>
<br>

If successful, you'll aid administrators, teachers, and students. Literacy curriculum developers and teachers who choose passages will be able to quickly and accurately evaluate works for their classrooms. Plus, these formulas will become more accessible for all. Perhaps most importantly, students will benefit from feedback on the complexity and readability of their work, making it far easier to improve essential reading skills.
</blockquote>
More details can be found [here](https://www.kaggle.com/c/commonlitreadabilityprize/overview/description).

While text embeddings using RoBERTa seem to be the most promising approach, I am applying GloVe embeddings in combination with sequence models to solve the task. A more in-depth explanation will follow after the final competition deadline.