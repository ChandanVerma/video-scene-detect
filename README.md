# video_scene_detect
```
video_path = 'path to .mp4 file'
scene_detect = VideoSceneDetect(video_path)
#scenes = scene_detect.find_shots()
saved_ = scene_detect.find_and_save_shots()
scene_detect.shots_to_features()
dist_mat = scene_detect.compute_similarity_matrix()
f = scene_detect.get_optimal_scene(dist_mat)
scene_detect.save_scenes(f, video_path)
```
