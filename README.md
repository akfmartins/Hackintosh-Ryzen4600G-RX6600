# Hackintosh EFI - Ryzen 4600G + RX 6600
EFI configurada para macOS Sequoia 15.4 em Ryzen 5 4600G + RX 6600 + Aorus Elite V2
Creditos Gabriel Luchina
https://github.com/luchina-gabriel/BASE-EFI-AMD-RYZEN-THREADRIPPER-PUBLIC

EFI funcional para macOS Sequoia 15.4 com:
- CPU: AMD Ryzen 5 4600G (iGPU desativada)
- GPU: AMD Radeon RX 6600
- Placa-mãe: Aorus Elite V2

## Recursos
- OpenCore 0.9.9
- Kexts: Lilu, WhateverGreen, VirtualSMC, AppleALC, etc.
- SMBIOS: iMac20,1

## Observações
- EFI testada apenas com iGPU desativada
- Para Wi-Fi/Bluetooth, use adaptador USB ou Broadcom compatível

⚠️ Dados sensíveis foram removidos do `config.plist` (MLB, ROM, serial, UUID)

📂 Estrutura final no GitHub/
├── EFI/
│   ├── BOOT/
│   └── OC/
│       ├── ACPI/
│       ├── Drivers/
│       ├── Kexts/
│       ├── config.plist
│       └── Tools/
└── README.md
