<!-- Gerado por manual-source/scripts/render-drivers.cjs a partir de data/drivers.json. Edite o catálogo, não este arquivo. -->
# Nitgen Hamster DX (HFDU06)

## Windows

Instalador da FingerTech (distribuidora da Nitgen). O driver específico do Hamster DX também fica na área logada do suporte FingerTech.

| Arquivo | Tamanho | SHA-256 | Origem |
| --- | --- | --- | --- |
| [Fingertech-Installer.exe](windows/Fingertech-Installer.exe) | 461 KB | `058468725fe5693bac82002cf112fd09cd887ac8e2842a436c07491abfea7a87` | [oficial ↗](https://fingertech.com.br/download/Fingertech-Installer.exe) |

## Linux

Driver Venus (código-fonte do módulo de kernel e SDK eNBSP), publicado pela FingerTech. Requer `build-essential` e `linux-headers-$(uname -r)`; depois `sudo make` e `sudo ./install-driver.sh`.

| Arquivo | Tamanho | SHA-256 | Origem |
| --- | --- | --- | --- |
| [venus-linux-driver-main.zip](linux/venus-linux-driver-main.zip) | 3,9 MB | `4ad4fd0be6ee4bdae0894c02b940acee6373897031f15207e6e9ce722ac09275` | [oficial ↗](https://github.com/FingerTechBR/venus-linux-driver) |

[← Voltar ao índice](../../README.md)
