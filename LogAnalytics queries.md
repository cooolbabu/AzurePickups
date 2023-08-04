### Function App
  FunctionAppLogs
  | where FunctionName == "<Function name>"

  FunctionAppLogs
  | where ExceptionDetails != ""  
  | order by TimeGenerated asc

  FunctionAppLogs
  | order by TimeGenerated desc
