---
title: "Serving LLMs on Arm: Running Rafay Token Factory on NVIDIA DGX Spark"
url: "https://rafay.co/ai-and-cloud-native-blog/serving-llms-on-arm-running-rafay-token-factory-on-nvidia-dgx-spark"
date: "2026-06-29"
author: "Mohan Atreya"
feed_url: "https://rafay.co/blog/"
---
Rafay's Token Factory now serves LLM inference on NVIDIA DGX Spark, an Arm-based Grace Blackwell superchip rather than traditional x86 hardware. The post walks through provisioning a Kubernetes cluster on the device, registering it as a compute cluster, and deploying a Qwen2 model with multi-tenancy, rate limiting, and metering, showing the platform abstracts away architecture differences.
