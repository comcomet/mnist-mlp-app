# mnist-mlp-app
이상하게 로컬에서도 서버 올라오고 다 잘돌아가고

Ainize 에 올려서 하면 
----> AINIZE 에서 main을 선택해야 합니다. default 인 feature/server 말구여...

[![Run on Ainize](https://ainize.ai/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=https://github.com/comcomet/mnist-mlp-app)


local

![local](https://user-images.githubusercontent.com/52145180/100236405-f8168480-2f70-11eb-95c5-5b5e5934d53c.png)


ainize
![ai1](https://user-images.githubusercontent.com/52145180/100236807-7f63f800-2f71-11eb-973d-ecc938910b5b.png)


anize 실행결과
![anizelast](https://user-images.githubusercontent.com/52145180/100300069-925de300-2fd8-11eb-8554-09199cbe0fb2.png)



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
