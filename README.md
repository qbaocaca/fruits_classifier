# FruitsClassifier on Fruits 360

<div align="center">
  <img alt="baocaca | fruits_gif" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/5ff09206-abe7-4bd5-9fcb-d7f039a12d92/d9icx2p-3019cef5-c78c-41c3-a1b5-1a064c3f1ee3.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzVmZjA5MjA2LWFiZTctNGJkNS05ZmNiLWQ3ZjAzOWExMmQ5MlwvZDlpY3gycC0zMDE5Y2VmNS1jNzhjLTQxYzMtYTFiNS0xYTA2NGMzZjFlZTMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TRXDHmIY3GAuDNY6EDzekCWcfye8KrHx29ZLsoli3Ao" />
</div>

### _On this project, I build a classifier on the Fruits 360 dataset using Pytorch. I use a pretrained model and transfer learning, as well as do hyper-parameter search to help increase the accuracy._

## 📺 **Youtube Videos:**

<!-- YOUTUBE:START -->
- [學長身材太好了，他害羞不敢看 🥰 中国电视剧](https://www.youtube.com/watch?v=WRF-Vafimaw)
- [Visualization in image classification.](https://www.youtube.com/watch?v=vzr0pAU0BC0)
- [Full Pytorch Training Pipeline on Image Classification](https://www.youtube.com/watch?v=tfYR8JMt0xA)
- [Chọn 1 tụ bài: Tình yêu bao giờ mới tới? &lpar;dành cho người độc thân&rpar;](https://www.youtube.com/watch?v=RM6eOxquOvo)
<!-- YOUTUBE:END -->

## **✍️ Documentation:**

### - _Full Training on [Kaggle] | GoogleNet | 94% Acc_

### - _Efficient Training with [Pytorch Lightning]_

&nbsp;

## **📰 Dataset structure**

    train/test
        |___apple_braeburn_1
            |___r0_0.jpg
            |___r0_10.jpg
                ...
        |___carrot_1
            |___r0_0.jpg
            |___r0_10.jpg
            ...

&nbsp;

## **Large batch visualization**

![batch](images/Fruits1.JPG)

&nbsp;

## **Separate visualization**

![se](images/Fruits2.JPG)

&nbsp;

## **Single fruit visualization**

![singbatch](images/Fruits3.JPG)

&nbsp;

## **Single fruit visualization with transforms**

![singtr](images/Fruits4.JPG)

&nbsp;

## **Separate visualization with transforms**

![setr](images/Fruits5.JPG)

&nbsp;

## **Batch visualization with transforms**

![batchtr](images/Fruits6.JPG)

&nbsp;

## **Pixel Intensity**

![pixel](images/pixel.JPG)

&nbsp;

## **Visualize the number of classes**

![class](images/class.JPG)

&nbsp;

## **Visualize loss and accuracy**

![lossacc](images/lossacc.JPG)

&nbsp;

## **Visualize model predictions: green(correct) and red(incorrect)**

![lossacc](images/pred.JPG)

[kaggle]: https://www.kaggle.com/code/alevi0989/fruits-360-googlenet-94-acc
[Pytorch Lightning]: https://qbaocaca.github.io/fruits_clf_lightning/
