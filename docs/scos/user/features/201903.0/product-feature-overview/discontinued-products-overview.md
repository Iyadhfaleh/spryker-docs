---
title: Discontinued Products Feature Overview
description: Discontinued products are shown during a certain period of time after the manufacturer or a distributor announces that the product is no longer produced.
last_updated: Jul 31, 2020
template: concept-topic-template
originalLink: https://documentation.spryker.com/v2/docs/discontinued-products-overview
originalArticleId: b7ce26a5-f609-498a-8024-87b2e9009020
redirect_from:
  - /v2/docs/discontinued-products-overview
  - /v2/docs/en/discontinued-products-overview
---

## Out of Stock vs. Discontinued Products
While we try to keep all the items in stock, we occasionally run out of products. In such a case the concrete product is tagged as out of stock and cannot be added to cart:
![Discontinued PDP](https://spryker.s3.eu-central-1.amazonaws.com/docs/Features/Product+Management/Discontinued+Products/Discontinued+Products+Feature+Overview/discontinued-pdp-page.png) 

Once the stock is updated with the positive number - the concrete product will be available for purchase.

Products are **discontinued** when the manufacturer or a current distributor has communicated that the product will no longer be produced. Still, the discontinued product may have stock (the stock number can either be positive or negative).

Discontinued products have a certain period of time when they will still be shown on the website (active_until). After this period ends - the products will become deactivated.

{% info_block warningBox %}
Only [concrete products](/docs/scos/user/features/{{page.version}}/product-feature-overview/product-feature-overview.html)
can become discontinued.
{% endinfo_block %} 

The schema below illustrates the relations between discontinued products, abstract and concrete products:
![Module relations](https://spryker.s3.eu-central-1.amazonaws.com/docs/Features/Product+Management/Discontinued+Products/Discontinued+Products+Feature+Overview/discontinued-schema.png) 

<!-- Last review date: Mar 1, 2019-- by Ahmed Sabaa, Yuliia Boiko -->
