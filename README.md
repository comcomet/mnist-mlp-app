# mnist-mlp-app
이상하게 로컬에서도 서버 올라오고 다 잘돌아가는대. 

Ainize 에 올려서 하면 "no healthy upstream" 이거만 자꾸 나오는지 모르겠습니다.

local

![local](https://user-images.githubusercontent.com/52145180/100236405-f8168480-2f70-11eb-95c5-5b5e5934d53c.png)


ainize
![ai1](https://user-images.githubusercontent.com/52145180/100236807-7f63f800-2f71-11eb-973d-ecc938910b5b.png)


no
![aino](https://user-images.githubusercontent.com/52145180/100236730-63f8ed00-2f71-11eb-8dbf-ad9b94d9b5b2.png)



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
