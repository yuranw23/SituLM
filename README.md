# SituLM: Leveraging Visual Instruction Tuning and an Augmented SWiG Dataset for Enhanced Grounded Situation Recognition

We present the augmented SWiG dataset and model checkpoints in this repository. Further details will be released.



## Augmented SWiG Dataset
The dataset consists of images and corresponding text annotations.
- Annotations: Found in "Augmented_SWiG/".
- Images: Download them [here](https://swig-data-weights.s3.us-east-2.amazonaws.com/images_512.zip).

### Directory Structure
- Training Set: `train_augmented.jsonl`
- Evaluation Set: `eval_augmented.json`
- Testing Set: `test_augmented.json`

## Model Checkpoints
### Trained with original SWiG dataset
- [Verb Classifier 7B](https://huggingface.co/YR23/llava-v1.5-7b-verb-classifier-2epoch)
- [Verb Classifier 13B](https://huggingface.co/YR23/llava-v1.5-13b-verb-classifier-2epoch)
- [Frame Detector and Localizer 7B](https://huggingface.co/YR23/llava-v1.5-7b-1epoch-gt-verb-without-cot)
- [Frame Detector and Localizer 13B](https://huggingface.co/YR23/llava-v1.5-13b-1epoch-gt-verb-without-cot)
- [Verb Frame Detector](https://huggingface.co/YR23/llava-v1.5-13b-1epoch)


### Trained with augmented SWiG dataset
- [Verb Classifier](https://huggingface.co/YR23/llava-v1.5-13b-verb-classifier-swig-augmented-2epoch)
- [Frame Detector and Localizer](https://huggingface.co/YR23/llava-v1.5-13b-gt-verb-swig-augmented-1epoch)
