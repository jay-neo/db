## `pwsh`

```pwsh
# Set Execution Policy as Remote Signed
Start-Process powershell -Verb runAs -ArgumentList "Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser" -PassThru -Wait
```

```pwsh
./pwsh/run.ps1
```

