# tweetlistener
```bash
git clone git@github.com:tu503/tweetlistener.git
cd tweetlistener
./build.sh

# make ~/env-file
cat ~/env-file
consumer_key=...
consumer_secret=...
access_token=...
access_token_secret=...
minio_hostname=localhost # minio not in play here

# then,
docker run --env-file ~/env-file developius/tweetlistener:latest

```
