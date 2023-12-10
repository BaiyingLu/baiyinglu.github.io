---
layout: page
title: Mealtime Prediction
description: Using pump data to predict meal time of people with diabetes
img: assets/img/mealtimelogo.png
importance: 2
category: work
giscus_comments: true
---
[Under review]
## Abstract
Many patients with diabetes struggle with post-meal high blood glucose due to missed or untimely meal-related insulin doses. To
address this challenge, our research aims to: first, study mealtime patterns in patients with type 1 diabetes using wearable insulin
pump data, and second, develop personalized models for predicting future mealtimes to support timely insulin dose administration.
Using two independent datasets with over 45,000 meal logs from 82 patients with diabetes, we find that the majority of people
(∼ 60%) have erratic and irregular mealtime patterns. We also show the feasibility of predicting future mealtimes with an
LSTM-based model that achieves an F1 score of > 95% with less than 0.25 false positives per day. Our research lays the
groundwork for developing a meal prediction system that can nudge patients with diabetes to administer bolus insulin doses
before meal consumption to reduce the occurrence of post-meal high blood glucose.

<div class="caption">
    Overview figure of the mealtime prediction study.
</div>
<div class="text-center">
    <div class="col-sm d-flex justify-content-center mt-3 mt-md-0">
        {% include figure.html path="assets/img/mealpred.png" title="mealpred" class="img-fluid rounded mx-auto d-block z-depth-1" width="90%" %}
    </div>
</div>


