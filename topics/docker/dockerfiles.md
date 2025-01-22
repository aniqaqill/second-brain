---
layout: default
description: "What I know about Dockerfile so far .."
---

## Built a Dockerfile

When I first started to learn about Docker, I literally had no idea what was happening until I tried to do something with it. So, it's best to start with something. Well, creating my own Dockerfile will probably help me to get started.
First thing first jus tinstall Docker in the machine [install Docker](https://docs.docker.com/engine/install/).

Let's get started.

![Anatomy of Dockerfile](../image/dockerfile.png)

As we can see, it consists of a few sections like **FROM, WORKDIR, COPY/ADD, RUN, EXPOSE, CMD/ENTRYPOINT**. Each of these has its own usage, as mentioned in the image.

So, I'm trying to understand what each of these actually does and what's the best way to initialize it. 

tbc..

I just now up till now then in existing repo you create a docker file by initalizaing `docker init` . It will somehow  analyze the projects and quickly create a Dockerfile,a `compose.yml`. [Read More](https://docs.docker.com/reference/cli/docker/init/)

So theres more than just what I thought is essentials as a software engineer who wants to containerized the app. It will be a good start to strat from dockerfile.

But there's always be more [here](https://docs.docker.com/reference/dockerfile/).A Dockerfile refference that have every single instruction and description for each and every command. Even I though its not necesaery to use each and every one of them. But its something that good to know and understand. It might be helpful in the coming future.


