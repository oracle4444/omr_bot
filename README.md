# omr_bot
Telegram bot for optical music recognition.

## Instruction

1. Get bot token from BotFather and save it in a file (for example "token").

2. Download docker image:
```
docker pull oracle4444/omr_bot
```

3. Run docker container:
```
docker run --mount type=bind,source=/path/to/token/dir,target=/home/token_dir oracle4444/omr_bot token_dir/token
```

## Example
<audio src="audio.mp3" controls preload></audio>
You send to the bot (no compression):

<img src="https://github.com/oracle4444/omr_bot/blob/main/omr_example.png"  width="547" height="691">

The bot send to you (in .ogg format):

https://github.com/oracle4444/omr_bot/assets/83769750/ade31b68-2c0f-4111-8c1a-ee019b90cb38

## Citation
Neural network for optical music recognition.

```
@Article{Calvo-Zaragoza2018,
  AUTHOR = {Calvo-Zaragoza, Jorge and Rizo, David},
  TITLE = {End-to-End Neural Optical Music Recognition of Monophonic Scores},
  JOURNAL = {Applied Sciences},
  VOLUME = {8},
  YEAR = {2018},
  NUMBER = {4},
  ARTICLE NUMBER = {606},
  URL = {http://www.mdpi.com/2076-3417/8/4/606},
  ISSN = {2076-3417},
  DOI = {10.3390/app8040606}
}
```

Neural network for staves detection.

```
 @article{damoyolo,
   title={DAMO-YOLO: A Report on Real-Time Object Detection Design},
   author={Xianzhe Xu, Yiqi Jiang, Weihua Chen, Yilun Huang, Yuan Zhang and Xiuyu Sun},
   journal={arXiv preprint arXiv:2211.15444v2},
   year={2022},
 }

 @inproceedings{sun2022mae,
   title={Mae-det: Revisiting maximum entropy principle in zero-shot nas for efficient object detection},
   author={Sun, Zhenhong and Lin, Ming and Sun, Xiuyu and Tan, Zhiyu and Li, Hao and Jin, Rong},
   booktitle={International Conference on Machine Learning},
   pages={20810--20826},
   year={2022},
   organization={PMLR}
 }

@inproceedings{jiang2022giraffedet,
  title={GiraffeDet: A Heavy-Neck Paradigm for Object Detection},
  author={yiqi jiang and Zhiyu Tan and Junyan Wang and Xiuyu Sun and Ming Lin and Hao Li},
  booktitle={International Conference on Learning Representations},
  year={2022},
}
```
