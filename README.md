# Workflow templates collection for reusability accross different projects

1. `dotnet_ci.yml` - workflow template used for tests execution. Supports both unit and integration tests. Integration tests are optional and require provision of appsettings data.
1. `dotnet_cd_az_function` - workflow template used for deployment to Azure Function.