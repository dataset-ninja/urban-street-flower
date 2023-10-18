Dataset **Urban Street: Flower Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/k/3/P4/g9hiOwLFjAV1ejpLz4jYTsYCqhe2nWt8fdT8qCESUSQfh20CWT28jpDsH3JW7lEQAJuTTrMwusnSQiaiwk7TcZrSpjjZcQyUiop8V4Rarbhp0VrV2FYrz1uRdLNE.tar)

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

