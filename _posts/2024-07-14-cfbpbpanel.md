---
layout:     post
title:      Install BPB Panel on Cloudflare
subtitle:    "\"CF BPB Panel\""
date:       2024-07-14
author:     CSRY
header-img: img/post-bg-2015.jpg
catalog: true
tags:
    - BPB
---
# Install BPB Panel on cloudflare

## Procedure
1. GitHub Fork [BPB Panel](https://github.com/bia-pain-bache/BPB-Worker-Panel) repository
2. Cloudflare create an pages application from the forked git repository.
3. Create KV namespace.
4. Bind the KV namespace to the application using variable name 'bpb'.
5. Add new environment variable 'UUID' with the new uuid generated.
6. Re-deploy the application.
   1. Deployments=>All Deployments=>...=>Retry deployment
7. Visit the {default application web page}/panel(default password is 'admin')
8. Change password.
9. Generate the subscription link and test with the client.

## Related github projects
BPB Panel: https://github.com/bia-pain-bache/BPB-Worker-Panel



—— CSRY 记于 2024.07 