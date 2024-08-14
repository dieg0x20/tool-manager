# Instalador de Ferramentas para Linux

Este script permite instalar várias ferramentas de desenvolvimento e utilitários em sistemas Linux baseados em Debian (como Ubuntu) de forma sequencial, com a possibilidade de selecionar quais ferramentas instalar através de parâmetros.

## Ferramentas Suportadas

- Git
- Curl
- Vim
- Htop
- Build-essential
- Docker
- Node.js e npm
- Python3 e pip
- nmap
- Gobuster
- ffuf
- Hydra
- Nuclei
- dirb

## Uso

1. **Torne o script executável**:

    ```bash
    chmod +x instalar_ferramentas.sh
    ```

2. **Execute o script com os parâmetros desejados**:

    ```bash
    ./instalar_ferramentas.sh [opções]
    ```

### Parâmetros Disponíveis

- `--git`: Instalar Git
- `--curl`: Instalar Curl
- `--vim`: Instalar Vim
- `--htop`: Instalar Htop
- `--build-essential`: Instalar Build-essential
- `--docker`: Instalar Docker
- `--nodejs`: Instalar Node.js e npm
- `--python`: Instalar Python3 e pip
- `--nmap`: Instalar Nmap
- `--gobuster`: Instalar Gobuster
- `--hydra`: Instalar Hydra
- `--ffuf`: Instalar ffuf
- `--dirb`: Instalar dirb
- `--nuclei`: Instalar Nuclei
- `--all`: Instalar todas as ferramentas acima
- `--help`: Mostrar a ajuda

### Exemplos

- Para instalar apenas Git e Vim:

    ```bash
    ./instalar_ferramentas.sh --git --vim
    ```

- Para instalar todas as ferramentas:

    ```bash
    ./instalar_ferramentas.sh --all
    ```
![image](https://uploaddeimagens.com.br/images/004/808/133/full/canivete.png?1720114403)


## Estrutura do Script

O script atualiza a lista de pacotes e instala as ferramentas especificadas nos parâmetros. Caso nenhum parâmetro seja passado, o script exibe a ajuda e termina a execução.

### Atualização da Lista de Pacotes

```bash
sudo apt update
```
#
<div align="center">
 <p>
  feito por <a href="https://github.com/dieg0x20">Diego Francisco</a> e os aliens
</p>
  <img style="width: 50px;" src="https://lowsec-community.vercel.app/assets/alien.png" alt="alien"/>
</div>

