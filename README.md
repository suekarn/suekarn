proxies:

- name: VMESS vidio
  type: vmess
  server: 104.22.4.240
  port: 80
  uuid: d7c408a4-3ceb-4829-91e2-a1b915c58c28
  alterId: 0
  cipher: auto
  tls: false
  servername: vmess-sg01.globalssh.xyz
  network: ws
  ws-opts: 
   path: /vmess-ws
   Headers: 
      Host: vmess-sg01.globalssh.xyz
  udp: true
  skip-cert-verify: true 
