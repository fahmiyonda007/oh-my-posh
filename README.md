# oh-my-posh $PROFILE
oh-my-posh init pwsh --config 'C:\Users\User\AppData\Local\Programs\oh-my-posh\themes\1_shell.omp.json' | Invoke-Expression | Set-PSReadLineOption -PredictionSource History | Set-PSReadLineOption -PredictionViewStyle ListView | Set-PSReadlineKeyHandler -Key Tab -Function MenuComplete
