# 📋| Sistema Gerenciador de Tarefas em C (To-Do List)

Um sistema de gerenciamento de tarefas via terminal simples, eficiente e direto, desenvolvido inteiramente na linguagem C. Este projeto foi criado como parte de uma avaliação prática da disciplina de Introdução à Programação do curso de Ciência da Computação do Instituto Federal do Ceará (IFCE) - Campus Tianguá, com o objetivo de aplicar conceitos fundamentais no gerenciamento de dados estruturados.

## 🚀| Funcionalidades

- **📝 Criação de Tarefas:** Adicione tarefas informando título, descrição e nível de prioridade (1 a 5).
- **🗂️ Listagem Inteligente:** Visualize todas as suas tarefas ordenadas automaticamente pela prioridade utilizando o algoritmo *Bubble Sort*.
- **✅ Conclusão de Tarefas:** Marque suas tarefas pendentes como concluídas de forma rápida informando seu ID.
- **🗑️ Remoção Segura:** Exclua tarefas da sua lista com etapa de confirmação para evitar perdas acidentais.
- **💾 Persistência de Dados (Save/Load):** O sistema salva suas tarefas automaticamente em um arquivo binário (`tarefas.bin`) ao sair, garantindo que nada seja perdido quando o programa for fechado. O carregamento ocorre de forma invisível ao abrir o aplicativo novamente.
- **🛡️ Tratamento de Entradas:** O sistema conta com validações personalizadas (`fgets` e limpeza de *buffer*) para evitar estouro de caracteres, loops infinitos e entradas vazias.

## 🖥️| Conceitos Técnicos Aplicados

Este projeto põe em prática pilares essenciais da programação em C:

1. **Estruturas de Dados (`struct`):** Modelagem da entidade das tarefas.
2. **Alocação Dinâmica de Memória (`malloc`, `realloc`, `free`):** O vetor de tarefas cresce ou encolhe sob demanda, evitando o desperdício de memória RAM.
3. **Ponteiros e Manipulação de Vetores:** Para reordenação (Sorting) e exclusão com deslocamento lateral de array.
4. **Manipulação de Arquivos (`FILE`, `fread`, `fwrite`):** Operações I/O binárias para persistência de estado.
5. **Algoritmo de Ordenação:** Implementação nativa de *Bubble Sort* para categorizar as prioridades de forma crescente.

## 🛠️| Como Executar o Projeto

**Pré-requisitos:** É necessário ter o compilador `gcc` instalado na sua máquina.

1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/gerenciador-tarefas-c.git](https://github.com/SEU-USUARIO/gerenciador-tarefas-c.git)
   cd gerenciador-tarefas-c
II. Compile o arquivo fonte:
``bash
Bash
gcc main.c -o gerenciador
Execute o programa:

Linux (Nativo no Pop!_OS / Ubuntu / etc):

Bash
./gerenciador
Windows:

Bash
gerenciador.exe``bash
 
