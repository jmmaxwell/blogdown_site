---
title: Cost-sensative Classificaiton, IPS, and Tensorflow
date: '2017-04-03'
---

I really like docker because it allows me to do cool stuff experimentally without destroying my dev environment. So if you want to follow along and don't have docker set up, see these [instructions](https://docs.docker.com/engine/installation/).

I think the easiest way to get tensorflow working with jupyter is to run the following and then go to the URL it spits out:

```bash
docker run -it -p 8888:8888 gcr.io/tensorflow/tensorflow
```

On cost sensitive:

This is really cool: you can think of contextual bandits as cost sensative classification problems: predict(arm|context) where cost = IPS cost function


Papers:

Langford on IPS, offline evaluation, etc
https://arxiv.org/pdf/1003.5956.pdf

