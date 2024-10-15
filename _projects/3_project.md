---
layout: page
title: Trading off Qualities for Quantities in Matching for Bargaining
description: Matching platforms may do better with less information
img: assets/img/platform.jpg
importance: 3
category: working papers
---

(Full draft is available <a href="https://drive.google.com/file/d/11jqrhKSUbC4_tBKwWCOK_x-F3cGIFl-i/view?usp=sharing">here</a>)

Abstract  

This paper investigates the design of an optimal matching protocol for a two-sided platform, where profits are determined by subsequent decentralized bargaining between matched pairs of buyers and sellers facilitated by a centralized protocol. 

<div class="row">
    <div class="col-sm-12 d-flex justify-content-center mt-1 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/platform.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1. Matching Platform with Decentralized Bargaining 
</div>

The study focuses on horizontally differentiated products and heterogeneous buyer preferences. We introduce the concept of match quality as a measure for assessing how well a product aligns with a buyer’s preferences. While the platform can achieve the highest match quality by pairing buyers with their optimal matches and facilitating immediate acceptance at the bargaining equilibrium, we show that this strategy is suboptimal in scenarios where match failures occur due to supply shortages, as shown by the comparison between figure (a), the exact matching, and figure (b), the broad matching with mismatches, below:

<div class="row">
    <div class="col-sm-12 d-flex justify-content-center mt-1 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/improvebymis.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2. Improvement by Introducing Mismatches
</div>

The losses from the red segments of match failures in (a) will be reduced in size by the increments from a thicker market with the new mismatches in the yellow-shaded area and the new delayed exact matches in the green-shaded area in (b).

Our findings reveal that it is more profitable for the platform to trade off high match quality for a thicker market, even if it results in lower match quality. This trade-off is driven by the incentives for buyers and sellers to wait and screen the available options provided by the matching protocol. Specifically, when sellers exhibit a weak propensity to screen, the platform can deliberately create mismatches to prevent target pricing, thereby encouraging sellers to offer lower prices to serve a larger market, which compensates for the reduced match quality. However, the potential increase in match quantities is constrained by the cost of the delay on the buyer side during the screening process. We delineate the conditions under which the platform realizes a net gain by prioritizing market thickness over high-quality matches and characterize the optimal matching protocol within a binary-type framework.

Extensions to include more types and a variation on the cost structure are also discussed.



