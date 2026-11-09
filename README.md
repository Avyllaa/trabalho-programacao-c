# Sistema de Cadastro de Compras em C

## Descrição
Projeto desenvolvido para a disciplina de Programação de Software Básico em C.

O sistema permite cadastrar compras por meio de uma interface gráfica do Windows, calcular o valor total de cada compra e armazenar os registros em um arquivo de texto.

## Funcionalidades
- Cadastro de produtos, quantidades e preços unitários.
- Validação dos dados informados.
- Cálculo automático do valor total.
- Armazenamento das compras no arquivo `aval1234.txt`.
- Exibição das compras cadastradas.
- Cálculo do valor acumulado das compras.
- Limpeza dos campos da interface.

## Tecnologias utilizadas
- Linguagem C
- Biblioteca Windows API (`windows.h`)
- GCC / MinGW-w64
- Visual Studio Code

## Compilação

No Windows, com o GCC configurado:

```bash
gcc cadastro_compras.c -o cadastro_compras.exe -mwindows
```

## Execução

No PowerShell:

```powershell
.\cadastro_compras.exe
```

## Testes realizados

Foram cadastrados cinco produtos diferentes:

| Produto | Quantidade | Total |
|---|---:|---:|
| Teclado | 2 | R$ 200,00 |
| Mouse | 3 | R$ 150,00 |
| Monitor | 1 | R$ 800,00 |
| Webcam | 2 | R$ 251,00 |
| Headset | 4 | R$ 300,00 |

**Resultado: 5 compras cadastradas, totalizando R$ 1.701,00.**

## Arquivos principais

- `cadastro_compras.c`: código-fonte do sistema.
- `aval1234.txt`: registros utilizados nos testes.
