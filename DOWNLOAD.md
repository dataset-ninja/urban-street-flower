Dataset **Urban Street: Flower Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI3NjBfVXJiYW4gU3RyZWV0OiBGbG93ZXIgQ2xhc3NpZmljYXRpb24vdXJiYW4tc3RyZWV0Oi1mbG93ZXItY2xhc3NpZmljYXRpb24tRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiNnFXbzhvMktkdDJiajZTVlNMaG4wbTJqVWowZW5nMXl3NS81bjJFaWlzOD0ifQ==)

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