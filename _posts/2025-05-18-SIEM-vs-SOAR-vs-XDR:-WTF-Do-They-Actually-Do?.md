---
title: 'SIEM vs SOAR vs XDR: WTF Do They Actually Do?'
date: 2025-05-18T00:00:00Z
author: Remotely Root
description: 
categories: [Education, Beginner]
tags: [elif,cybersecurity,siem,soar,xdr]
---


# SIEM vs. SOAR vs. XDR: WTF Do They Actually Do?

For someone who is just getting their feet wet into cybersecurity, it can be overwhelming and confusing to hear the wide variety of tools a security professional may use. Defining them alone can be difficult if youre new, let alone have a concrete understanding of how they function and what they actually accomplish. Nevertheless, I hope you find this blog post useful, happy reading.

These three particular tools are pretty neat in the sense they form a synergy between one another. A bond between the SIEM, SOAR, and XDR produce quite a powerful security suite of tools. Their ability to ingest logs, monitor endpoints, and use that data to create alerts is quite crucial to the defense of an organizations environment. It's us against them in this world and this suite of tools provides a leg up against our adversaries. I recently took a SANS course and one of the greatest take aways was a statement "malware can hide, but it must run", meaning if it runs, you can find it... if youre good enough. 

To effectively generate alerts we first need to ingest our data into a Security Information Event Manager - commonly referred to as SIEM (pronounced 'SEAM' or 'SIM'). We cannot properly create effective alerts that create 'True Positives' without ingesting our logs to a centralized point. With this process, we have the ability to correlate data points and create advanced detection alerts. More on that later in the SOAR section and after we cover XDR/EDR as well. 



