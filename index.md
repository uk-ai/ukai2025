---
layout: home
title: Index
---

# Registration and Abstract Submission

To register for the conference and/or submit an abstract, please use this form: **[{{ site.data.conference.submission.name }}]({{ site.data.conference.submission.url }}){:target="_blank"}**

Please see the **[Call for Papers]({{ "call-for-papers.html" | relative_url }})** for instructions.

For questions and queries please contact Christian Cabrera: [chc79@cam.ac.uk](mailto:chc79@cam.ac.uk)

# Key Dates 

{% include listdates.html %}

# Venue

The conference will be hosted at {{ site.data.conference.venue }}, {{ site.data.conference.location }}. More details on the venue can be bound [here](https://uk-ai.org/ukai2024/venue.html).

# Organizing Committee

{%if site.author.email %}General inquiries should be sent to [{{ site.author.email }}](mailto:{{ site.author.email }}).{%endif%}

{% include listallchairs.html program_committee=true %}


