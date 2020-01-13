# 360action
A New Data Set :: 360-Degree Actions

DATASET DESCRIPTION
-------------------

We introduce 360Action, the first omnidirectional video dataset for action
recognition. Different from conventional action recognition datasets,
360Action contains 360-degree videos which capture multiple person performing
multiple actions at the same time.

The dataset contains 784 diverse videos, recorded using a state-of-the-art
omnidirectional camera, Kodak PixPro SP360 4K, which has a horizontal FoV of
360-degree and a vertical FoV of 235-degree. All videos have a high resolution
of 2880x2880.

### Scenes

360Action consists of videos from 10 diverse scenes including 2 indoors scenes
(lobby, convenience store) and 8 outdoor scenes (stadium yard, stadium gate,
carpark night, carpark day, train station gate, train station platform, yard 1
and yard 2).

Different scenes have different environments and different lighting
conditions. The diversity of scenes puts high requirement on the algorithm to
be robust to different conditions.

### Subjects

We hired 80 different subjects for video recording. 40 subjects are male and
40 subjects are female. The ages of the subjects range from 10 to 40 years
old. Each subject is assigned a consistent ID number across all videos. We
split subjects with IDs 1-60 into training set, and subjects with IDs 61-80
into test set.

### Actions

The dataset contains 19 classes of daily actions, including 15 single-person
actions: walking, running, eating, drinking water, waving hand, picking up
something, dropping something, taking off jacket, wearing jacket, making phone
call, playing phone, walking upstairs/downstairs, tapping into/out of station
4 interactions: pushing someone, handshaking, taking something from someone,
giving something to someone. During recording, we assign each subject a
scripted set of actions to perform. Each subject performs each action at least
once in a scene. In each video, multiple subjects perform multiple actions
concurrently. The maximum number of concurrent actions in a video is 7. On
average, each video contains 4 concurrent actions,


SAMPLES of VIDEO CLIPS
----------------------

- Small size (720x720)

![Scene1A_14.mp4](videos/small/Scene1A_14.mp4)
![Scene1B_84.mp4](videos/small/Scene1B_84.mp4)
![Scene2_22.mp4](videos/small/Scene2_22.mp4)
![Scene3A_55.mp4](videos/small/Scene3A_55.mp4)
![Scene4A_4.mp4](videos/small/Scene4A_4.mp4)
![Scene4B_17.mp4](videos/small/Scene4B_17.mp4)
![Scene5A_48.mp4](videos/small/Scene5A_48.mp4)
![Scene5B_20.mp4](videos/small/Scene5B_20.mp4)
![Scene6A_47.mp4](videos/small/Scene6A_47.mp4)
![Scene6B_59.mp4](videos/small/Scene6B_59.mp4)


Obtaining the Dataset
---------------------

If you want to use this dataset, please contact [jqliu (AT) nec.com](mailto:jqliu@nec.com).
When using this dataset, please cite the following two publications:

```
@inproceedings{LiLWNK20,
  author    = {Junnan Li and
               Jianquan Liu and
               Yongkang Wong and
               Shoji Nishimura and
               Mohan S. Kankanhalli},
  title     = {Weakly-Supervised Multi-Person Action Recognition in 360{\textdegree} Videos},
  booktitle = {{IEEE} Winter Conference on Applications of Computer Vision, {WACV}
               2020, Colorado, USA, March 1-5, 2020},
  pages     = {xxx--xxx},
  year      = {2020}
}

@inproceedings{LiLWNK19,
  author    = {Junnan Li and
               Jianquan Liu and
               Yongkang Wong and
               Shoji Nishimura and
               Mohan S. Kankanhalli},
  title     = {Self-supervised Representation Learning Using 360{\textdegree} Data},
  booktitle = {Proceedings of the 27th {ACM} International Conference on Multimedia,
               {MM} 2019, Nice, France, October 21-25, 2019},
  pages     = {998--1006},
  year      = {2019},
  url       = {https://doi.org/10.1145/3343031.3351019},
  doi       = {10.1145/3343031.3351019}
}
```

### Copyright

This dataset is only allowed to use for academic research without any commercial purpose. All copyrights are reserved by the authors and original providers. This dataset is available on request to the authors of the following publications.

### Publications

1. Junnan Li, Jianquan Liu, Yongkang Wong, Shoji Nishimura, Mohan S. Kankanhalli:
  Weakly-Supervised Multi-Person Action Recognition in 360° Videos. **WACV 2020**: xxx-xxx.
  
2. Junnan Li, Jianquan Liu, Yongkang Wong, Shoji Nishimura, Mohan S. Kankanhalli:
  Self-supervised Representation Learning Using 360° Data. **ACM Multimedia 2019**: 998-1006.
