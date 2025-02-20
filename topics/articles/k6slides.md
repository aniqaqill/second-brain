---
marp: true
footer: "PayNet Data Lake & Analytics | Aniq Aqil" 
---

![w:60 h:60](../image/k6logo.png) ![w:60 h:60](../image/grafanalogo.png)

# Introduction to k6 

![bg right:60% margin-right: 90% drop-shadow:0,5px,10px,rgba(0,0,0,0.6)](../image/testcode.png)

---

# Overview

1. What is k6 ?
2. What is Load testing ? 
3. Why Do Performance Testing?
4. Load Testing vs. Performance Testing
5. Load Test Scenarios/Types
6. Chaos and Infrastructure testing
7. QuickPizza Demo
8. Data-Gateway Current Workflow

---

# What is k6?

- Grafana k6 is an open-source, developer-friendly, and extensible load testing tool. k6 allows you to prevent performance issues and proactively improve reliability.

---

# What is Load Testing ?
- Load testing is the process of putting demand on a system and measuring its response.
- **Key Points**
    - Focuses on how well a system works under load.
    - Different from functional testing which checks if a system works.
    - Measures qualitative aspects like responsiveness and reliability.

---

# Why Do Performance Testing?

## Benefits:
- Improve user experience.
- Identify bottlenecks early.
- Prepare for unexpected demand.
- Increase confidence in the application.
- Assess and optimize infrastructure.

---

## Common Excuses & Counterpoints:

- "Our application is too small" → Even small systems benefit.
- "It's expensive/time-consuming" → Cost of not testing is higher.
- "Requires extensive technical knowledge" → Range of complexity available.
- "We don’t have a performance environment" → Alternatives exist.
- "The cloud is infinite" → Efficiency still matters.

---

# Load Testing vs. Performance Testing


```js 
                Performance testing != Load testing 
```


- Performance testing verifies how well a system works as a whole, including aspects such as scalability, elasticity, availability, reliability, resiliency, and latency. 

- Load testing is just one type of performance testing, and it is an approach that can be used to test many of aspects of application performance. However, not all performance testing involves load testing.

- Load testing is a sub-practice of performance testing.

---

# Load Test Scenarios

A load test scenario combines specific values of test parameters. Each scenario recreates a certain situation or set of conditions that the application will be exposed to.

Load test scenarios are often called load test types. Some of the most common scenarios are listed here.

---

##### Shakeout Test 

**Small test to check for major issues.**
Sometimes known as a smoke test, checks for major issues before spending more time and resources.

- Typically uses one or a few VUs that run for a short amount of time . If **test fails** any issues must be resolved first. 

```js
Name: Shakeout Test
Total VUs: 5	
Ramp-up: 0 seconds	
Duration: 10 minutes
Ramp-Down: 0 seconds
```

![bg right:40% margin-right: 90% drop-shadow:0,5px,10px,rgba(0,0,0,0.6)](../image/shakeout.png)

---

#### Average Load Test**: Simulates typical production load.


---

- **Stress Test**: Simulates peak load conditions.

---

- **Soak Test**: Long-duration test to identify degradation over time.

---

- **Spike Test**: Simulates sudden traffic spikes.

---

- **Breakpoint Test**: Identifies the load level at which performance degrades.

---

# Demo by Grafana Labs

---

# Demo by Grafana Labs

This demo is provided by grafana labs itself. Was named QuickPizza demo app. 

- [k6-workshop](https://github.com/aniqaqill/k6-oss-workshop)
- [QuickPizza](https://github.com/grafana/quickpizza)

Lets go through the demo !


---

# How data-gateway utilized k6

---

# Extras: Chaos testing 

Hello from mars :satellite:

---

# Sources

- [k6 Learn](https://github.com/grafana/k6-learn)
- [k6 OSS Workshop](https://github.com/grafana/k6-oss-workshop?tab=readme-ov-file#before-we-start)
- [Awesome k6](https://github.com/grafana/awesome-k6)
- [Load Testing with k6](https://levelup.gitconnected.com/load-testing-with-k6-48488c7946bb)
- [k6 Operator for K8s](https://github.com/grafana/k6-learn/blob/main/Modules/XX-Future-Ideas/How-to-use-the-k6-operator-for-Kubernetes.md)
- [Chaos testing with k6 and Friends](https://www.youtube.com/watch?v=2QHs_HEX7r0)
- [Basic k6 Load Testing Setup](https://youtu.be/XR2MAivt-9E?si=IlauKGqcsVKGx3rC)
- [Chai with k6](https://grafana.com/docs/k6/latest/testing-guides/use-chai-with-k6/)

