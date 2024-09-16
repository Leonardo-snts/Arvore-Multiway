# Arvore-Multiway

Este sistema utiliza uma árvore MultiWay para armazenar os registros dos medicamentos, garantindo buscas eficientes. Cada registro de medicamento contém os seguintes campos:

- Código (Chave): Identificador único do medicamento
- Nome: Nome do medicamento.
- Quantidade: Quantidade disponível no estoque.
- Preço Unitário: Preço por unidade do medicamento.
- Preço Total: Preço total (calculado nas vendas).
- Timestamp: Data e hora da venda ou devolução.

## Sobre o Projeto
Este programa é um sistema que gerencia o estoque de medicamentos de uma farmácia, permitindo ao usuário:

- Adicionar Medicamento ao Estoque: Insere um novo medicamento ao sistema, com código, nome, quantidade e preço unitário.
- Vender Medicamento: Remove uma quantidade especificada de medicamento do estoque e registra a venda.
- Devolver Medicamento: Registra a devolução de medicamentos e atualiza o estoque.
- Relatório Diário: Gera um relatório das vendas e devoluções realizadas.
- Visualização da Árvore: Imprime a árvore contendo os medicamentos armazenados.

## Requisitos

Para compilar e rodar o sistema, você precisará de:

- Um compilador C (como GCC)
- Ambiente Linux ou Windows com suporte para compilação em C

### Como Executar

Clone este repositório:

```
git clone https://github.com/Leonardo-snts/Arvore-Multiway.git
```
Navegue até o diretório do projeto:

```
cd Arvore-Multiway
```

Compile o programa utilizando o compilador C (por exemplo, GCC):

```
gcc arvore2.c -o gerencia_medicamentos
```

Execute o programa:

```
./gerencia_medicamentos
```

Siga as instruções do menu para realizar as operações desejadas.
