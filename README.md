# samsam
Testing Meta AI Computer Vision Research Segment Anything Model (SAM)

# prep

```
python3 -m pip install --upgrade pip
python3 -m pip install git+https://github.com/facebookresearch/segment-anything.git
python3 -m pip install opencv-python pycocotools matplotlib onnxruntime onnx
python3 -m pip install torch torchvision torchaudio opencv-python
python3 -m pip install matplotlib
python3 -m pip install --upgrade numpy
```

TODO: chk complete requirements

# models

download from TODO

`ls -ltr models/*.pth > models/models.txt`

# code
```
python3 scripts/ez_amg.py --checkpoint "models/sam_vit_h_4b8939.pth" --input "images/IMG_3636.jpg" --output Output

python3 scripts/ez_amg.py --checkpoint "models/sam_vit_h_4b8939.pth" --input "images/_f04e26e5-0a97-4228-a968-b0a26413f339.jpeg" --output Output
```