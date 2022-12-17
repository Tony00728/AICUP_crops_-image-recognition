**:bug:AICUP2022_農地作物現況調查影像辨識競賽:bug:**
=
[農地作物現況調查影像辨識競賽](https://aidea-web.tw/topic/5f632f38-7213-4d4d-bea3-117ff13c1afb)
-

**指導教授:劉宗榮**

**隊伍名稱:Team_2043**

**隊長:方峻梃，組員:陳語嫣、廖浩翔、謝東格、張祐嘉**


**Installation Environment**
-
   ```
  作業系統: Windows10(x64)
  硬體設備: 3090-Ti
  語言: Python 
  撰寫軟體:PyCharm
  額外資料集:比賽提供的圖片以程式做資料增強
  Package Version 
  absl-py 1.0.0 / cachetools 4.2.4 / certifi 2021.10.8 / charset-normalizer 2.0.12 
  cycler 0.11.0 / google-auth 1.35.0 / google-auth-oauthlib 0.4.6 / grpcio 1.44.0 
  idna 3.3 / imageio 2.17.0 / imgaug 0.4.0 / importlib-metadata 4.11.3 / joblib 1.1.0 
  kiwisolver 1.4.2 / Markdown 3.3.6 / matplotlib 3.2.1 / networkx 2.6.3 / numpy 1.21.6 
  oauthlib 3.2.0 / opencv-python 4.2.0.34 / packaging 21.3 / pandas 1.0.4 / Pillow 9.1.0 /
  pip 22.0.4 / prefetch-generator 1.0.1 / protobuf 3.20.0 / wheel 0.37.1 /
  pyasn1 0.4.8 / pyasn1-modules 0.2.8 / pyparsing 3.0.8 / python-dateutil 2.8.2 /
  pytz 2022.1 / PyWavelets 1.3.0 / requests 2.27.1 / requests-oauthlib 1.3.1 /
  rsa 4.8 / scikit-image 0.19.2 / scikit-learn 0.23.1 / scipy 1.4.1 / seaborn 0.10.1 /
  setuptools 62.1.0 / Shapely 1.8.1.post1 / six 1.16.0 / tensorboard 2.2.2 / torch 1.5.0 /
  tensorboard-plugin-wit 1.8.1 / threadpoolctl 3.1.0 / tifffile 2021.11.2 / torchvision 0.6.0 typing_extensions 4.2.0 / 
  urllib3 1.26.9 / Werkzeug 2.1.1 / zipp 3.8.0/
 ```


**Models**
-
在資料夾models，DeiT III 、volo_d4、volo_d5、convNext:、Swin Transforme
都有用使用，並且取其中最為有效的。
 
VOLO 提供 D1 到 D5 不同複雜程度的模型，詳細差別可以查看下表

![This is an image](https://miro.medium.com/max/4800/1*ZBqHS6G_PdOTOyZJsw6e_w.webp)
  
  
  
  
  
  
   
**Rerfence**
-
**Paper - [DeiT III: Revenge of the ViT](https://arxiv.org/abs/2204.07118)**

