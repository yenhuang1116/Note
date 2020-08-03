# bsdiff 原始碼建置問題 

>[參考連結](https://docs.docker.com/engine/reference/commandline/create/)

1. $ docker create -t -i ubuntu:latest bash
6d8af538ec541dd581ebc2a24153a28329acb5268abe5ef868c1f1a261221752
2. $ docker start -a -i 6d8af538ec5
bash-4.2#
3. $ docker start -a -i 6d8af538ec5
4. cat /etc/*-release
