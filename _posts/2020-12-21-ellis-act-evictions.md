---
title: "Ellis Act Evictions in San Francisco, from March 2020 onwards"
date: 2020-12-21
published: true
tags: [dataviz, hvplot]
excerpt: "A look at where Ellis Act Evictions have occured since March 2020"
hv-loader:
  hv-chart-1: ["charts/side_by_side.html", "1200"] 
toc: true
toc_sticky: true
---

The COVID-19 rental protection for tenants in San Francisco does not apply to evictions due to Ellis Act. The Ellis Act is a controversial law that allows a landlord to leave the rental business and evict all tenants in the building. Some argue this can be used by the property owner to circumvent rent control laws. 

The COVID-19 eviction ban started in March 2020, thus the data has been filtered for Ellis Act evictions that occurred from March 2020 onwards. The issue in question could be whether or not landlords are using the Ellis Act to evict tenants who may not be able to afford rent (but cannot be evicted for nonpayment due to the COVID exemption). Since there are no strict criteria for invoking the Ellis Act, it could be a proxy for landlords wanting to evict their tenants. 

The number of Ellis Act evictions that occured in San Francisco, grouped by neighborhoods, from March 2020 onwards can be seen in the table below. 

![ellis-evictions-table]({{ site.url }}{{ site.baseurl }}/assets/images/ellis_act_eviction_png.png)

It appears that there is the highest number of Ellis Act evictions in the Mission (15) and Outer Mission (6) neighborhoods. Interestingly, when the point data is plotted on the map below, there are just 3 data points in the Mission neighborhood, which could indicate a building at a singular geographical location  with multiple tenants being evicted.  

![point-ellis-evictions]({{ site.url }}{{ site.baseurl }}/assets/images/point-ellis-evictions.png)

## Median Household Incomes in San Francisco 

The Mission neighborhood also has one of the lowest median household incomes in San Francisco, as seen in the choropleth map below. The data is pulled from ACS 5-year data on median household incomes by census tract. 

![medhhincome]({{ site.url }}{{ site.baseurl }}/assets/images/medhhincome.png)

## 311 Requests - Homeless Concerns in San Francisco 

Data on 311 requests in San Francisco has been obtained from SF Open Data. 

The visualizations below show a side-by-side comparison of where Ellis Act evictions have occurred in San Francisco and 311 homeless concern requests, from March 2020 onwards. There appears to be an overlap between areas that experience a higher incidence of Ellis Act evictions and 311 homeless concern requests. The highest concentration of homeless concerns is also observed in the Mission neighborhood, which also sees the highest concentration of Ellis Act evictions. Taking into consideration the fact that the Mission neighborhood also experiences one of the lowest median household incomes in SF, this could paint a concerning picture. As this could suggest that renters are being evicted from their apartments and potentially rendered homeless.

<div id="hv-chart-1"></div>

