# mnist-mlp-app
이상하게 로컬에서도 서버 올라오고 다 잘돌아가는대. 
Ainize 에 올려서 하면 "no healthy upstream" 이거만 자꾸 나오는지 모르겠습니다.


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
