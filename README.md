# proxapi
connect to proxmox api 
code automatization proxmoxer
from proxmoxer import ProxmoxAPI
proxmox = ProxmoxAPI(
    "your.proxmox.domain.or.ip",  # URL Proxmox API
    token_name="root@pam!automation-token",  # формат: user@realm!tokenid
    token_value="SECRET_TOKEN_HERE",          # секрет токена
    verify_ssl=False                           # True, если сертификат валидный
)
