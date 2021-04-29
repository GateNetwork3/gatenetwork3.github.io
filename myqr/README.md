# myqr
## QR Code scanner for login hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```html
<button onclick="window.location='https://github.com/GateNetwork3/QRscan';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="GateNetwork QR Code Scanner" disabled=no dst-host=github.com
```

### Powered by webqr.com