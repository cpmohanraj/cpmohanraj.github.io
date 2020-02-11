---
layout: post
title: "Setting Azure Budget Alert"
date: 2020-02-11
---

Since I had no choice of using the free account, I wanted to set an alert for any cost overrun for the new account (subscription) that I created. When I navigated to Cost Management --> Budgest section in Azure portal, I was shown an message saying that the scope (scubscription level) was not supported for budgets. I was surprised as I have seen this working before at my work place. I have tried changing the scope to a resource group and even tried creating a vm to check whether it would allow me to set a budget, but no luck.

I only had limited time to try more things but a quick google search didn't help either. I gave up and left to do other things with frustration. 

Many hours later, I went back to the computer and tried setting up an alert for cost and Voila!, it worked this time at the subscription scope. I assumed that some background processing (which could take few hours) had to finish to have the cost management section working.

On to learning more...
