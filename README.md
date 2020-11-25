# mnist-mlp-app
This application simply translates hand written number 2 at /images as digit number 2
based on mlp model training.

[![Run on Ainize](https://ainize.ai/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=https://github.com/comcomet/mnist-mlp-app)


## Acknowledgement
This mnist-mlp code snippet derived from [Keras team](https://github.com/keras-team/keras/blob/keras-2/examples/mnist_mlp.py).

## How to install thru Docker
```sh
sudo docker build -t mnist-mlp-app .
```

## How to run thru Docker
```sh
sudo docker run -p 80:80 mnist-mlp-app
```
