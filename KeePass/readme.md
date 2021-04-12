# KeePass

## Configuring KeePass to launch RDP

Go to `Tools`, `Options`, `URL Scheme overrides`, `Add`.

Enter scheme `rdp`.
Enter URL override: 

```
cmd://cmd /c "cmdkey /generic:TERMSRV/{BASE:HOST} /user:{USERNAME} /pass:{T-REPLACE-RX:/{PASSWORD}/(.)/^$1/} && start /b mstsc /v:{URL:RMVSCM} && timeout /t 5 /nobreak && cmdkey /delete:TERMSRV/{BASE:HOST}"
```

Now your can use urls like `rdp://a.host.com`


Source: http://blog.bitcollectors.com/adam/2014/04/launching-rdp-keepass-2-x-auto-login/