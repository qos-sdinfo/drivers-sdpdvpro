<!-- Gerado por manual-source/scripts/render-drivers.cjs a partir de data/drivers.json. Edite o catálogo, não este arquivo. -->
# 📥 Drivers - SDPDVPRO

Repositório oficial de drivers de impressoras e periféricos homologados para uso com o SDPDVPRO, separados por **Windows** e **Linux**. Cada modelo tem um README com os arquivos, o tamanho, o SHA-256 e a origem oficial de cada um.

> **Regra de comunicação das impressoras (manual, seção 2.3):** conexão COM (serial) usa ESC/POS; conexão USB usa ACBR. A comunicação via ACBR ainda não é suportada no Linux.

## 🖨️ 01. Impressoras

| Marca | Modelo | Windows | Linux | Observações | Detalhes |
|---|---|---|---|---|---|
| **Bematech** | MP-4200 TH | [📁 Windows](./01-impressoras/bematech-mp-4200-th/windows/) | [📁 Linux](./01-impressoras/bematech-mp-4200-th/linux/) | Mude a configuração para XON/XOFF e para ESC/POS. | [README](./01-impressoras/bematech-mp-4200-th/README.md) |
| **Bematech** | MP-4200 HS | [📁 Windows](./01-impressoras/bematech-mp-4200-hs/windows/) | [📁 Linux](./01-impressoras/bematech-mp-4200-hs/linux/) | - | [README](./01-impressoras/bematech-mp-4200-hs/README.md) |
| **Elgin** | i7 Plus | [📁 Windows](./01-impressoras/elgin-i7-plus/windows/) | [📁 Linux](./01-impressoras/elgin-i7-plus/linux/) | Via ACBR, selecione o modelo Epson equivalente. A Elgin só publica arquivos para a i7 Plus. | [README](./01-impressoras/elgin-i7-plus/README.md) |
| **Elgin** | i8 | [📁 Windows](./01-impressoras/elgin-i8/windows/) | [📁 Linux](./01-impressoras/elgin-i8/linux/) | Funciona melhor em modo Virtual COM. No SDPDVPRO, use ESC/POS (não ACBR) como serial. | [README](./01-impressoras/elgin-i8/README.md) |
| **Elgin** | i9 e i9 FULL 2 | [📁 Windows](./01-impressoras/elgin-i9/windows/) | [📁 Linux](./01-impressoras/elgin-i9/linux/) | Via ACBR, selecione o modelo Epson equivalente. | [README](./01-impressoras/elgin-i9/README.md) |
| **Epson** | TM-T20 | [📁 Windows](./01-impressoras/epson-tm-t20/windows/) | — | A Epson não lista driver Linux para a TM-T20 no Epson Download Center (consulta de 17/11/2026). | [README](./01-impressoras/epson-tm-t20/README.md) |
| **Epson** | TM-T20X | [📁 Windows](./01-impressoras/epson-tm-t20x/windows/) | [Site do fabricante ↗](https://download-center.epson.com/softwares/?device_id=TM-T20X&os=DEBX64&language=en&region=BR) | Sendo testada em Linux. | [README](./01-impressoras/epson-tm-t20x/README.md) |
| **Daruma** | DR700 D | [📁 Windows](./01-impressoras/daruma-dr700d/windows/) | — | - | [README](./01-impressoras/daruma-dr700d/README.md) |
| **Daruma** | DR800 D | [📁 Windows](./01-impressoras/daruma-dr800d/windows/) | — | - | [README](./01-impressoras/daruma-dr800d/README.md) |
| **Sweda** | A confirmar | Pendente | Pendente | Pendente: aguardando a equipe confirmar o modelo. | [README](./01-impressoras/sweda/README.md) |

## ⚖️ 02. Balanças (Checkout e Pesagem)

| Marca | Modelo | Conexão | Observações | Acesso à Pasta |
|---|---|---|---|---|
| *(Aguardando upload)* | - | - | - | [📁 Acessar](./02-balancas/) |

## 📟 03. Postes de Preço (Torres)

| Marca | Modelo | Conexão | Observações | Acesso à Pasta |
|---|---|---|---|---|
| *(Aguardando upload)* | - | - | - | [📁 Acessar](./03-postes-cliente/) |

## ☝️ 04. Leitores biométricos

| Marca | Modelo | Windows | Linux | Observações | Detalhes |
|---|---|---|---|---|---|
| **Futronic** | FS81 | [📁 Windows](./04-leitores-biometricos/futronic-fs81/windows/) | [📁 Linux](./04-leitores-biometricos/futronic-fs81/linux/) | O FS81 usa o driver da família FS80 publicado pela Futronic. | [README](./04-leitores-biometricos/futronic-fs81/README.md) |
| **Control iD** | iDBio | [📁 Windows](./04-leitores-biometricos/controlid-idbio/windows/) | [📁 Linux](./04-leitores-biometricos/controlid-idbio/linux/) | - | [README](./04-leitores-biometricos/controlid-idbio/README.md) |
| **Nitgen** | Hamster DX (HFDU06) | [📁 Windows](./04-leitores-biometricos/nitgen-hamster-dx/windows/) | [📁 Linux](./04-leitores-biometricos/nitgen-hamster-dx/linux/) | - | [README](./04-leitores-biometricos/nitgen-hamster-dx/README.md) |

## 🔧 05. Drivers Genéricos

| Descrição do Driver | Aplicação | SO | Observações | Acesso à Pasta |
|---|---|---|---|---|
| *(Aguardando upload)* | - | - | - | [📁 Acessar](./05-drivers-genericos/) |

## 🛠️ 06. Utilitários e Testes

| Ferramenta | Aplicação Prática | SO | Observações | Acesso à Pasta |
|---|---|---|---|---|
| *(Aguardando upload)* | - | - | - | [📁 Acessar](./06-utilitarios-testes/) |
