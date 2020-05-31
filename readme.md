# SSH TEST

## Reference article
https://blog.jaycetyle.com/2018/02/github-ssh/


## Step

1. generate ssh public and private key.

    `$ssh-keygen`

2. you can skip the passphrase so you don't need to key in passphrase later on

3. Find where the key is store, say, user "everything"
3. Copy the public key inside xxx.pub file
4. Go Github "settings:
   1. Find option to enter SSH key
   2. Enter your choose name to enter title/name
   3. Paste the key
5. Now you can use SSH to push/pull

