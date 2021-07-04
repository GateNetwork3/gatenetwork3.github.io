#myqr

QR Code scanner for login hotspot MikroTik

Cara pakai 
Tambahkan button di login.html

<button onclick="window.location='https://gatenetwork3.github.io/myqr';">QR Code</button>

Tambahkan script berikut di MikroTik via Terminal.

/ip hotspot walled-garden ip
add action=accept comment="GateNetwork QR Code Scanner" disabled=no dst-host=gatenetwork3.github.io

Powered by webqr.com
