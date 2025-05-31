## ML Flow Experiments

```import dagshub
import dagshub
dagshub.init(repo_owner='MadarwalaHussain', repo_name='ml-flow-experiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
  ```