---
title:  "Looking back at SAP HANA"
date:   2017-03-28 20:30:00
categories: [publications]
tags: [datascience, bigdata, physics, SAP]
comments: true
---
<a style="text-align: center" href="http://www.itnewsafrica.com/2015/03/nuclear-physicist-takes-a-deeper-look-into-sap-hana/">
  <img src="http://www.itnewsafrica.com/wp-content/uploads/2014/07/SAP-300x225.jpg">
</a>

Shortly after my transition from academia to the enterprise world of SAP, I published an
[article in ITNews Africa](http://www.itnewsafrica.com/2015/03/nuclear-physicist-takes-a-deeper-look-into-sap-hana/).
At the time I was in the midst of rapid cross-skilling into the world of enterprise (SAP) technology.
I couldn't help but notice how the value-adds of in-memory computing echoed the staples of big data processing in big physics (ie. Nuclear/Particle Physics experiments):
- Flexibility
- Scale
- Layers of data structures

Looking at [the article](http://www.itnewsafrica.com/2015/03/nuclear-physicist-takes-a-deeper-look-into-sap-hana/),
a few years later, though embarassed by the blatant product-pushing, I'm quite proud at how the emphasis on virtual data structures/models has remained relevant.

I'm currently back to the open-source world, working with the Apache big data stack, and in our data pipeline, virtualization is king.  Layers of views, with layers of cacheing on top of Hadoop, combined with the flexibility of arbitrarily complex Python transformations in Pyspark means that as a Data Scientist **I'm free to ask the questions that need asking**.

Whereas SAP HANA, a fantastic enterprise tool, will deliver well on traditional, well-defined use cases closely coupled to the SAP business processes, it will quickly lose it's shine in the hands of a demanding analyst or data scientist.
The diversity and complexity of queries in a modern data science workflow can only be delivered by an open source stack.

These are two different worlds that are both needed in the enterprise.  Today, I'll push another idea to which I've been aspiring our infrastructure towards: Databricks' [just-in-time data warehouse](http://go.databricks.com/data-warehousing-solution-from-databricks).  
![the concept of a *just in time data warehouse* conceptualized by Databricks](http://go.databricks.com/hs-fs/hubfs/JIT-overview-image3.png.jpeg?noresize&t=1495748704479&width=1140&name=JIT-overview-image3.png.jpeg)

If you're not familiar with what Databricks is about, I recommend heading over to [their website](https://databricks.com/).
Of course, there are many angles with which to approach data in your organization.  I warn against a strategy that does not include a modern component.
