# termux-playit-script
idk just a script to install playit on a smarthpone. i love hosting servers on random devices
## The Script

```bash
curl -SsL https://playit-cloud.github.io/ppa/key.gpg | gpg --dearmor | tee /etc/apt/trusted.gpg.d/playit.gpg >/dev/null && echo "deb [signed-by=/etc/apt/trusted.gpg.d/playit.gpg] https://playit-cloud.github.io/ppa/data ./" | tee /etc/apt/sources.list.d/playit-cloud.list && apt update && apt install playit
```

## Why did i do whis
i have no idea lmao, i just removed all the sudo's in the original script lol
