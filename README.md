If you want to test this repo:
1. increase the rev number plus 1 in `webhooks-test-app/index.html`
2. build dockerfile and push the image to the dockerhub
3. After success deploy your app will be updated and you see updated number of rev

For login to dockerhub use command
docker login

For building a image use commands
```
docker build --tag uffizzitest/webhooks-test-app .
docker login
docker push uffizzitest/webhooks-test-app:latest
```
