#Zoom Auth microservice
# DEVELOPER GUID
How to run docker image?

cd cleark /n
docker build .
docker run <ID that genrated>

<!-- eg:   docker run sha256:18fcb44ca2485db132a92aeee0f10cf868e58969b5013afd3220bbc59e50213c -->

How to kill docker terminal?

docker ps
copy CONTAINER ID
docker kill <CONTAINER ID>
<!-- eg: docker kill e3de97091930 -->

How to install eslint?

In PowerShell as Administrator, you could try the following:

CMD: Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted


https://www.digitalocean.com/community/tutorials/linting-and-formatting-with-eslint-in-vs-code

add this extra rules to eslint config
  rules: {
    quotes: [2, 'single', { avoidEscape: true }],
    semi: [2, 'always']

  }
