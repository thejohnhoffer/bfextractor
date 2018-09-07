source your environment variables, like `source ~/.env`, then:

```
sudo aws s3 sync s3://minerva-test-cf-common-rawbucket-5stex9f1o6pq /data
sudo -E docker-compose up -d --build
sudo -E docker-compose logs -t -f
```
