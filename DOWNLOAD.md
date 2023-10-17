Dataset **Panoramic Dental X-rays** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/y/A/DS/FTOXPbAvBdm8A0JANQyP2rQjfd0O9tMQ3kkE2EVvHXxXuC9ygQ5wB9rkIcV3DXEdgJvbZYIFRxOta4PkJdYrW2qHgWzhjeTr2SRFpGXtT8MX7i0eOqNun9z8zV2z.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Panoramic Dental X-rays', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

