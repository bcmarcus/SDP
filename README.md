https://github.com/THU-MIG/yolov10

# setup

## Download weights
```bash
# wget https://github.com/THU-MIG/yolov10/releases/download/v1.1/yolov10{n/s/m/b/l/x}.pt
# for instance
wget https://github.com/THU-MIG/yolov10/releases/download/v1.1/yolov10n.pt
```

```bash
python -m pip install -r requirements.txt
```

## With gpu
```bash
python -m pip install onnxruntime-gpu
```

# run code
```bash
python detection.py 
```

## saving
conda env export --no-builds > environment.yml
