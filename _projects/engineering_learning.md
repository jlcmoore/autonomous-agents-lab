---
layout: page
title: Engineering Interactive Learning in Artificial Systems
description: >
    We look to develop machines that learn through autonomous exploration of and interaction with their environments -- as humans learn. To do this, we use deep reinforcement learning and employ and develop techniques in curiosity, active learning, and self-supervised learning. In doing so, we hope to create artificial systems that can learn more autonomously, flexibly, and robustly, with less demand on data.
img: assets/img/engineering_learning/teaser.avif
importance: 1
category: work
related_publications: true
---

Most successful machine learning algorithms of today rely on either carefully curated, human-labeled datasets, or extremely large amounts of interactive experience with simple environments. This reliance has critical drawbacks: the expansive and careful human effort in curating the data is expensive, and models trained in this way struggle to generalize beyond the scope of the data. In short, current AI is data-hungry, and in particular, for large-scale, carefully-crafted human input. This creates challenges, not only of expense and scale, but also of ethics: the desire to collect more and better data conflicts with people’s desire for privacy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/human_learning/environment_reduced_size.avif" title="A reduced sized environment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    {% cite kim_active_2020 %}
</div>

People, on the other hand, learn by virtue of their agency: they interact with various environments, exploring and building complex mental models of their world so as to flexibly adapt to a wide variety of tasks. This loop of action and perception is inseparable from the human learning process, as they decide what to look at, how to manipulate objects, and what to say to others.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/human_learning/sample_complex_latest.avif" title="Various graphs depicting agent performance" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    {% cite kim_active_2020 %}
</div>

Thus far, we have developed curious, self-supervised deep reinforcement learning agents that explore and learn to model 3D physical environments and other agents. In doing so, they gain predictive models  and useful visual representations. In the long term, we would like to grow these learning algorithms into a variety of robust technologies:

- Curious, exploring robots that autonomously adapt to new surroundings and perform a variety of tasks. 

- Social AI that interacts with you and understand your beliefs & understandings. 

- AI that accesses, harnesses, and welds human knowledge.


{% cite haber_learning_2018 %}

{% cite mrowca_flexible_2018 %}
