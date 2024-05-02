# aiModel
- ipynb 파일은 구글 코랩을 통해 사본을 깃허브에 저장한 것
- pothole20240429.pt : 코랩에서 코드를 실행해 100번의 에폭을 통해 생성된 best.pt
- pklot20240429.vol1, vol2 : 코랩에서 코드를 실행해 생성된 best.pt. 깃허브 25mb 제한으로 인해 분할 압축


```
!python train.py --img 416 --batch 16 --epochs 100 --data ./hard_hat_workers/data.yaml --cfg ./models/custom_yolov5s.yaml --weights '' --name _result --cache
```
