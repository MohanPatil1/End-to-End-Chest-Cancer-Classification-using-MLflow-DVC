
# End-to-End-Chest-Cancer-Classification-using-MLflow-DVC

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml

### cmd
- mlflow ui
...
### dagshub
[dagshub](https://dagshub.com/)
---
MLFLOW_TRACKING_URI=https://dagshub.com/MohanPatil1/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME=MohanPatil1 \
MLFLOW_TRACKING_PASSWORD=b012f118dc3d6b379af50b064849498a546dd303 \
python script.py

Run this to export as env variables:

```bash
set MLFLOW_TRACKING_URI=https://dagshub.com/MohanPatil1/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC.mlflow

set MLFLOW_TRACKING_USERNAME=MohanPatil1

set MLFLOW_TRACKING_PASSWORD=b012f118dc3d6b379af50b064849498a546dd303
... 