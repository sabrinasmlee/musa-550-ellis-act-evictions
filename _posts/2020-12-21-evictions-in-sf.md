---
title: "Evictions in San Francisco, from 2003 to 2016"
date: 2020-12-21
published: true
tags: [dataviz, hvplot]
excerpt: "A look at where evictions occur in SF from 1997 to 2020"
hv-loader:
  hv-chart-1: ["charts/choropleth.html", "500"] # second argument is the height
toc: true
toc_sticky: true
---

The COVID-19 pandemic presents a looming eviction crisis in America. As unemployment rates have surged, current policy responses such as the CARES Act may be insufficient to provide families with enough support. While states such as California have passed temporary eviction moratoria, once these measures expire, renters will oew landlords a significant amount of rent back. A displacement and eviction crisis may follow the public health crisis. 

California State Law AB-3088 prevents tenants from being evicted due to missed payments for March to August 2020 rent, but renters still owe the rent. Starting March 1, 2021, landlords can sue tenants in small claims court to seek a court judgments confirming they owe rent, and then try to use the judgment to collect the payment. Under the San Francisco Mayor's Order, until November 30, 2020, evictions for reasons other than nonpayment can proceed only if necessary due to violence, threat of violence, and health/ safety issues. The rental protection for tenants in San Francisco also does not apply to evictions due to Ellis Act. 

The visualizations below show where evictions have occurred in San Francisco, from 2003 to 2016. Areas that show high eviction rates over the years are likely to experience higher rates of eviction as a result of the economic impacts of COVID-19, and it would be important to pay attention to these areas for a potential eviction crisis. 


## Evictions in San Francisco 

Below shows a plot of eviction cases in San Francisco from 2003 to 2016. It can be observed that there is a high incidence of eviction cases in the northeast and southwest areas of the city. 

![evictions-2013to2016]({{ site.url }}{{ site.baseurl }}/assets/images/SF_evictions_2013to2016.png)


The interactive plot below allows us to observe the incidence of eviction cases year-by-year, from 2003 to 2016. It can be observed that the same areas of the city experience higher eviction cases, since 2003. 

<div id="hv-chart-1"></div>

