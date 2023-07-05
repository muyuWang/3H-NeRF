# 3H-NeRF
With only a minor change, our model can also support pose editing and novel view synthesis. We only need to train another simple NeRF model for the torso after the THG module and then connect it to the SRT module.
We present the experimental results of our method for novel view synthesis and pose editing here. 

<div align=center>
<img src="https://github.com/muyuWang/3H-NeRF/blob/main/novel_view1.png" width="900" height="300">
</div>

`novel_view1.png` shows the novel views of the portraits we generate. From left to right, the left view, front view and right view are respectively shown.

<div align=center>
<img src="https://github.com/muyuWang/3H-NeRF/blob/main/novel_view2.png" width="900" height="300">
</div>

`novel_view2.png` shows the top view, front view and up view.

Our method can also support pose editing. `original_pose.mp4` is the evalution results with its original pose. `new_edited_pose.mp4` is the video generated with an edited posed 
and `fixed_pose.mp4` is generated with a fixed pose. You can play them simultaneously for better comparison as `play_together.mp4`.
