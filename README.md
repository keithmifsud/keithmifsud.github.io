# My Website


## Notes

Notify



When updating images in the `src/` directory, I needed to refresh cache. Deleting the `_sites` directory is not enough.

```bash

jekyll clean && jekyll build


```

**Serve & Force Polling on Jekyll**

```bash

jekyll serve --force_polling --host=0.0.0.0

```

**Check Jekyll Serve Process ID (PID)**

```bash

ps aux | grep jekyll

```


**Kill Jekyll serve Process**

```bash

kill -9 "XXX"

```





**Todo:** <br/>

- Issue with gulp's cached images.
So far chnaging to master, pishiong and pullinhg worked after

```bash

jekyll clean && jekyll serve --force_polling --host=0.0.0.0

```
