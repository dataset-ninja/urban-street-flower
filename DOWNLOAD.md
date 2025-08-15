Dataset **Urban Street: Flower Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjc2MF9VcmJhbiBTdHJlZXQ6IEZsb3dlciBDbGFzc2lmaWNhdGlvbi91cmJhbi1zdHJlZXQ6LWZsb3dlci1jbGFzc2lmaWNhdGlvbi1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJrcVdXLzRjRmhXYXhiMDZSSHU2MXE3TGs2ZHZPR3VmUHBZREEzcG43L2F3PSJ9?response-content-disposition=attachment%3B%20filename%3D%22urban-street%3A-flower-classification-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Urban Street: Flower Classification', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/erickendric/tree-dataset-of-urban-street-classification-flower).