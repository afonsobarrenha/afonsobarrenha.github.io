---
layout: post
title:  "AWS - Amplify - Host Static Website"
date:   2022-11-28 22:32:00 -0300
categories: jekyll update
---
Seguindo o tutorial hands-on da AWS "[Hospede um site estático](https://aws.amazon.com/getting-started/projects/host-static-website?trk=gs_card)" como um primeiro contato com o serviço AWS Amplify.

Primeiro site estático servido através do Amplify, mas com uma surpresinha desagradável no final: por default, ele aloca uma máquina com 4 processadores e 8 GB de memória :@

Corri para apagar a aplicação no Amplify, e corri também para ver se não havia ficado nada "para trás" no serviço de EC2 como máquinas ou como Volumes.

Mas no final, sucesso, e código-fonte em [afonsobarrenha/amplify-host-static-website](https://github.com/afonsobarrenha/amplify-host-static-website).