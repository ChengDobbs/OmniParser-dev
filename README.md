# OmniParser-dev
 
[[OmniParser V2, icon_caption, icon_detect](https://huggingface.co/microsoft/OmniParser-v2.0/tree/main)] 

[[PaddleOCR V5](https://www.paddleocr.ai/main/en/version3.x/pipeline_usage/OCR.html#1-ocr-pipeline-introduction)] 

If `PADDLE_PDX_CACHE_HOME` env variable is not set, the models (`~200MB`) will automatically be downloaded to `~/.paddlex` (`~/.paddlex/official_models`). PaddleOCRV5 uses 3 models in a pipeline manner (`PP-LCNet_x1_0_textline_ori`, `PP-OCRv5_server_det`, `PP-OCRv5_server_rec`) to get the final result.

### Install 
Clone the repo first, and then install environment:
```python
cd OmniParser
conda create -n "omni" python=3.10
conda activate omni
pip install -r requirements.txt
```