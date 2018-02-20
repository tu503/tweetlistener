# tweetlistener
```bash
git clone git@github.com:tu503/tweetlistener.git
cd tweetlistener
./build.sh

# make ~/env-file-x
cat << EOF > ~/env-file-x
consumer_key=...
consumer_secret=...
access_token=...
access_token_secret=...
minio_hostname=localhost # minio not in play here
EOF

# then,
docker run --env-file ~/env-file-x developius/tweetlistener:latest

docker pull python:2.7-alpine

```
