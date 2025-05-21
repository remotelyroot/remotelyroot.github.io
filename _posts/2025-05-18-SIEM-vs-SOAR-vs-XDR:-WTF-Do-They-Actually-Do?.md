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

## Security Information Event Manager (SIEM)

A SIEM in its nature is a log aggregation tool. If you're using a SIEM, you are aggregating all of your logs or 'collecting' all of your Firewall, IDS/IPS, Proxy, DNS, Endpoint, EDR/XDR, to name a few into a centralized location. When these logs are ingested, the SIEM (depending on vendor) attempts to *normalize* the log data to provide some uniformity. Ensuring there is log normalization will help parsing through the thousands of events that occur per hour in your environment. For example, if your Firewall logs have a field designated as 'destination_ip' and your IDS/IPS has a field that is named 'target_ip', we may want to *normalize* the proposed data into a common, arbitrary field name like 'dest_ip'. So when an analyst or whomever is sifting through the data on the SIEM, all they need to do is designate the 'dest_ip' to retrieve destination/target ip for both the Firewall and IDS/IPS logs. 

There are many other functions of a SIEM, event correlation and alerting are two of those powerful functions. Correlation events allows the analyst or engineer to curate a search that connects endpoints logs with network logs. Having the ability provides an efficient way to catch complex attacks and reduce false positives, which is what we want. False Positives, if not properly identified could lead to wasted hours by security analysts and engineers. 


## Security Orchestration, Automation, and Response (SOAR)




## XDR Extended Endpoint Detection and Response




### References

