➤ STEP 1:

Run the following command to install crave.

Note: you just need to run it once in your instance. ONLY ONCE!!

```
bash <(curl -s https://raw.githubusercontent.com/musivian/crave_termux/refs/heads/main/install.sh)
```

➤ STEP 2:
Now, you'll need the crave.conf from foss.crave.io you can do so by going to https://foss.crave.io/app/#/apikeys

Download the key
use some text editor to copy it's contents
now go to your segfault instance, run nano crave.conf & simply paste the things here (by the 'things', I refer to the json content of config)
So, now you finally have installed crave and also you have your config in your instance.

➤ STEP 3:
Connecting to crave's devspace

Now, you can connect to devspace by running ./crave -c crave.conf devspace And finally you will land in crave's devspace.

YAAAY !! (again)
