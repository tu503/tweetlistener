# tweetlistener
```bash
git clone tweetlistner
cd tweetlistener
./build.sh

# make ~/env-file
cat ~/env-file
consumer_key=...
consumer_secret=...
access_token=...
access_token_secret=...
minio_hostname=...

# then,
docker run --env-file ~/env-file developius/tweetlistener:latest

```
