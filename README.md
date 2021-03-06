# Alive_Images


This repository uses code from [first order model](https://github.com/AliaksandrSiarohin/first-order-model) and openCV to generate alive photos.

## Install modules
```
pip3 install -r requirements.txt
```

## Inference
Download pretrained model [here.](https://drive.google.com/drive/folders/1PyQJmkdCsAkOYwUyaj_l-l0as-iLDgeH). 
You only need to down "vox-adv-cpk.pth.tar"

Extract model and put it in "checkpoints" dir.


```
python3 demo.py  --config config/vox-adv-256.yaml --driving_video driving_video/short.mp4 --source_image source_image/friends.jpeg --checkpoint checkpoints/vox-adv-cpk.pth.tar --relative --adapt_scale
```

## Select face in the image
![](https://github.com/farazBhatti/Alive_Images/blob/master/gif/gif-1.gif)

## Final result
![](https://github.com/farazBhatti/Alive_Images/blob/master/gif/gif-2.gif)

### To do
- Apply multiple faces reenactment


## Acknowledgment

- [first-order-model](https://github.com/AliaksandrSiarohin/first-order-model)



