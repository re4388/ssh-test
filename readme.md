# SSH TEST

## Reference article
https://blog.jaycetyle.com/2018/02/github-ssh/


## Step

1. generate ssh public and private key.

    `$ssh-keygen`

1.1 you can skip the passphrase so you don't need to key in passphrase later on

2. then you can check by yourself where the key stre
3. copy the public inside xxx.pub
4. go to github "settings:
   1. find place to enter SSH key
   2. enter your choose name to enter title/name
   3. paste the key you copied from xxx.pub
5. And then you later will be able to use SSH to push/pull
