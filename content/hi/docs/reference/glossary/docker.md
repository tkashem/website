---
title: डॉकर (Docker)
id: docker
date: 2018-04-12
full_link: https://docs.docker.com/engine/
short_description: >
  डॉकर एक सॉफ्टवेयर टैकनोलजी है जो ऑपरेटिंग-सिस्टम-स्तरीय वर्चुअलाइजेशन प्रदान करता है जिसे कंटेनर भी कहा जाता है।

aka:
tags:
  - fundamental
---

डॉकर (विशेष रूप से, डॉकर इंजन) एक सॉफ्टवेयर टैकनोलजी है जो ऑपरेटिंग-सिस्टम-स्तरीय वर्चुअलाइजेशन प्रदान करता है जिसे {{< glossary_tooltip text="कंटेनर" term_id="container" >}} भी कहा जाता है।

<!--more-->

डॉकर लिनक्स कर्नेल के संसाधन अलगाव सुविधाओं का उपयोग करता है, जैसे कि cgroups और कर्नेल नेमस्पेस, और एक संघ-सक्षम फ़ाइल सिस्टम जैसे कि OverlayFS और अन्य स्वतंत्र कंटेनरों को एक लिनक्स इंस्टेंस के भीतर चलाने की अनुमति देता है| इससे वर्चुअल मशीन (वीएम) को शुरू करने और बनाए रखने के ओवरहेड से बच सकते हैं|