+++
image = "/img/about-bg.jpg"
categories = ["Development","kubernetes"]
tags = ["kubernetes", "About"]
date = "2017-03-13T11:59:10-07:00"
title = "Announcing KUBE2GO"
comments = true
draft = false
description = "Announcing KUBE2GO the easiest way to run your cluster"
+++

Announcing Kube2go

At Platform9, we have not only made containers a core part of our overall product strategy, 
but have also gone all-in with Kubernetes as the container orchestration framework of choice. 
Over the last couple of years, as Kubernetes has risen to become the most popular container 
orchestration engine, it has been great to see the community come together and work towards making it successful.
As our own small effort to aid this growth, we are very proud, today, to announce Kube2Go to the Kubernetes 
community – the easiest way to run Kubernetes clusters on any major public cloud! Simply sign up / register, and quickly create highly available clusters on AWS, with support for GCE and Azure coming in future updates. Make sure to have the AWS access and secret key handy before you register. Once the cluster is created you can:

#### Download kubeconfig for [kubectl]( https://kubernetes.io/docs/user-guide/kubectl-overview/) ####
![Kube2go Dashboard](/images/kubernetes-pf9.png)
 

#### View the [Dashboard](https://kubernetes.io/docs/user-guide/ui/): ####
![Kubernetes Dashboard](/images/kubernetes-dashboard.png)


#### Simply launch a CLI right from the web-browser: ####
![Kubernetes Dashboard](/images/kubernetes-webcli.png)



In this first incarnation, we’re focussing on making cluster creation and usage drop-dead simple for our users. As we continue to iterate, along with adding more cloud providers, our focus will be on making the consumption of Kubernetes clusters easier, by simplifying application development using [“Helm”](https://github.com/helm/) charts and even integrating serverless functions-as-a-service via [Fission](http://fission.io). 
To top it all of, this is completely free for up to five nodes within your cluster! So try out Kube2Go today, and let us know what you think at info@kube2go.io
