Dataset **Powerline Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/u/z/yU/m57MKPVmdCqksGlWsqIxHCJfNN5NQUZruh0qNroPcAtDUdvVQqp1YV8lad6bTXV49rMhOpBHTOZMnaGgRGq2B4bwxdpGAIJHvd90Q0lRwRgCpb2xHhu087JzNNo2.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Powerline Detection', dst_path='~/dtools/datasets/Powerline Detection.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/college-2t4kc/powerline-detection/dataset/5/download)