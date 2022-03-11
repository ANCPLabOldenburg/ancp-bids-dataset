# ancp-bids-dataset
Test datasets to use with ancpBIDS.

# usage

``` python
from ancpbids import fetch_dataset, BIDSLayout
# downloads dataset 'ds005' into user's home directory '~/.ancbids/datasets/ds005'
dataset_path = fetch_dataset('ds005')
layout = BIDSLayout(dataset_path)
layout.get_subjects()
```
