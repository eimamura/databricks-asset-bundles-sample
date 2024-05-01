# databricks-asset-bundles-sample

```bash
choco install databricks-cli
databricks auth login --host <workspace-url>
databricks auth profiles
databricks auth token --host <workspace-url> -p <profile-name>
databricks bundle init
cd my_dbab
databricks bundle validate
databricks bundle deploy
databricks bundle destroy
```