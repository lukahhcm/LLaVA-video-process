# LLaVA-Video-Process

A tool for extracting and tracking frames containing faces from the **LLaVA-Video-178K** dataset, specifically the **0_30_s_youtube_v0_1** subset.

## Dataset

The dataset can be found on Hugging Face: [LLaVA-Video-178K](https://huggingface.co/datasets/lmms-lab/LLaVA-Video-178K).

## Installation

To install, please follow the setup instructions provided in [facebookresearch/sam2](https://github.com/facebookresearch/sam2).

## Running the Video Processing Script

Navigate to the `sam2` directory and run the following command:

```bash
cd sam2
python key_frame.py
```

The script will generate a `Tracked_Data` folder with processed frames and output a `filtered_output.jsonl` file in the `LLaVA_video_with_face` directory.

**Note:** Ensure that the file paths in `key_frame.py` are correctly set before running the script.
