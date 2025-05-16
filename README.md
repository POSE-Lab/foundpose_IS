# _IS

Run foundpose on IndustryShapes:


Download the IndustryShapes dataset from [here](https://huggingface.co/datasets/POSE-Lab/IndustryShapes) . You can then use the instructions in foundpose to setup and run the model.
For the config files, we opted to use the default configuration, as per the lmo files.


In the [inference config](https://github.com/facebookresearch/foundpose?tab=readme-ov-file#3-inference-), where the configs/infer/industryshapes.json will be created, set the variable "use_detections" to true if you want to use CNOS detections, or false for ground truth masks.

```json
"use_detections": true # CNOS predictions
"use_detections": false # GT masks
```
