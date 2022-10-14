# JAVA MINIMAL CI/CD

![GitHub last commit](https://img.shields.io/github/last-commit/gerardVM/java-spring-ci-cd)

This Error page coded in Java is containerized automatically by GitHub Actions, pushed to Docker hub and updated in my Kubernetes deployment every time the branch main is updated.

## Usage

Clone this repository and start your app from it. Be aware that you will have to adapt the kubectl instructions in the workflow manifest changing the name of your container in your Kubernetes cluster. After that, you just set the secrets DOCKER_IMAGE_NAME, DOCKER_USERNAME, DOCKER_TOKEN and KUBE_CONFIG_DATA (This last one needs to be encoded in base64) and let GitHub Actions do its magics. 

(You need an account in Docker hub)

## Contributing

Pull requests are welcome

## License

[MIT](LICENSE.txt)

