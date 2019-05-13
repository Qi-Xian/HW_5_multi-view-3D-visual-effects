## a.Take multi-view images by ourselves

我們再小吃部前取景，multi_view部分的資料集請參閱

1. [multiview1_資料夾](https://github.com/Qi-Xian/HW_5_multi-view-3D-visual-effects/tree/master/multi_view1)
2. [multiview2_資料夾](https://github.com/Qi-Xian/HW_5_multi-view-3D-visual-effects/tree/master/multi_view2)

### 校景（找到相同的 allignment的feature match）
<img src='multi_view2/stitched.jpg' width = "640" height="480">
<img src='multi_view2/matchesOfPanorama_1.jpg' width = "640" height="480">
<img src='multi_view2/matchesOfPanorama_2.jpg' width = "640" height="480">
<img src='multi_view2/matchesOfPanorama_3.jpg' width = "640" height="480">

### 杯子multi_view（背景blur效果）
<img src='multi_view2/DSC_4241.JPG' width = "640" height="480">
<img src='multi_view2/DSC_4242.JPG' width = "640" height="480">

## b. Show image alignment results between different images

在alignment, Motion Parallax呈現，如下圖與source code連結。

<img src='Motion parallax/Motion parallax.gif' width = "640" height="480">

[程式碼連結/Downloads](https://drive.google.com/file/d/1jk72tJ9wHROH4z565PjWAhtO1d9P3etD/view)

## c. Generate the multi-view 3D visual effects
我們使用校景的資料夾，使用SIFT偵測來找出feature match,找出之後，再輸出成動態圖。
<img src='stop Motion/stop Motion.gif' width = "640" height="480">

一個人定位在中間，同樣使用sift偵測做出stop Motion effect，如下圖。

<img src='stop Motion2/stop Motion_2.gif' width = "640" height="480">

接下來，Live photo部分，我們一樣也都用SIFT演算法找到一個定位點，效果上還可以呈現。

<img src='live_photo/live photo.gif' width = "640" height="480">

[程式碼連結/HW_5.ipynb](https://colab.research.google.com/drive/1T1AhY79seiNjtU7YFA-nY-0XJLZnTQk0)
## d.Exploit creativity to add some image processing to enhance effect (Using post-production software is allowed)



## e. 結論

## f. 參考文獻
