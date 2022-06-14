# Datasets
Dataset 설명

# Segmentation
## Videos Matting
### Youtube VIS(Video Instance Segmentation)
- tasks for simultaneous detection, segmentation, tracking object in videos
- current largest video object segmentation
- best model: Mask2Former
- 2,883 high-resolution YouTube videos, 2,238 training videos, 302 validation videos and 343 test videos
- A category label set including 40 common objects such as person, animals and vehicles
- 4,883 unique video instances
- 131k high-quality manual annotations

### PPM-100 (portrait matting)
- fine annotation: annotated carefully + detailed
- natural background: original Background, not synthetic distribution(합성없음), 다만 background complexity는 다소 낮음
- rich diversity: images cover full/half body and various postures
- high resolution: between 1080p and 4k

### VideoMatte240K
- 484 high-resolution green screen videos 
- total of 240,709 unique frames of alpha mattes and foregrounds with chroma-key software Adobe After Effects.

### PhotoMatte13K/85
- 13,665 images
- shot with studio-quality lighting and cameras in front of a green-screen
- mattes extracted via chroma-key algorithms with manual tuning and error repair
