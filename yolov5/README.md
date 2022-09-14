## <div align="center">Start Examples</div>

<details open>
<summary>Install</summary>

Clone repo and install [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) in a
[**Python>=3.7.0**](https://www.python.org/) environment, including
[**PyTorch>=1.7**](https://pytorch.org/get-started/locally/).

```bash
git clone https://github.com/Jung-YongHan/yolov5.git  # clone
cd yolov5
pip install -r requirements.txt  # install
```

****기존 코드의 에포크는 300이지만 테스트를 위해 5로 바꾸었음***  
****training 및 testing 후 생성되는 runs-train(val)-exp 폴더에 결과물이 저장됨.***

</details>


```shell
├── yolov5
│   ├── README.md              
│   ├── setup.cfg              # model hyperparameters
│   ├── train.py               # training
│   ├── val.py                 # testing
│   ├── export.py              # Export a YOLOv5 PyTorch model to other formats.
│   ├── data                   # datasets for modeling
│   ├── models                 
│   │   ├── yolo.py                 # YOLOv5 architecture
│   ├── utils             
│   │   ├── activation.py 
│   │   ├── metrics.py 
│   │   ├── loss.py 
```