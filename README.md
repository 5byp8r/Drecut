<p align="center">
    <img src="https://github.com/user-attachments/assets/b72f6577-ab48-4fd5-843c-263c42bf8ce9" alt="Logo Drecut" width="320"/>
</p>

<h3 align=center>Drecut: Fragmentos da Verdade</h3>

<p align="center">
    <img alt="Python 3.14.6" src="https://img.shields.io/badge/Python-3.14.6-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img alt="pygame-ce 2.5.7" src="https://img.shields.io/badge/pygame--ce-2.5.7-FEE32D?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzIiIGhlaWdodD0iMzIiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPjxwYXRoIGZpbGw9InVybCgjYSkiIGQ9Ik0wIDBoMzJ2MzJIMHoiLz48ZGVmcz48cGF0dGVybiBpZD0iYSIgcGF0dGVybkNvbnRlbnRVbml0cz0ib2JqZWN0Qm91bmRpbmdCb3giIHdpZHRoPSIxIiBoZWlnaHQ9IjEiPjx1c2UgeGxpbms6aHJlZj0iI2IiIHRyYW5zZm9ybT0ic2NhbGUoLjAzMTI1KSIvPjwvcGF0dGVybj48aW1hZ2UgaWQ9ImIiIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSIgeGxpbms6aHJlZj0iZGF0YTppbWFnZS9wbmc7YmFzZTY0LGlWQk9SdzBLR2dvQUFBQU5TVWhFVWdBQUFDQUFBQUFnQ0FZQUFBQnplbnIwQUFBQUFYTlNSMElBcnM0YzZRQUFBQVJuUVUxQkFBQ3hqd3Y4WVFVQUFBQUpjRWhaY3dBQUVhOEFBQkd2QWZmOVM0UUFBQUdpU1VSQlZGaEh0WllCcm9RZ0RFVDM2QnpObTdsQkdHbGZBWkgvZDVMSmFvWE90QmF6bjg4NnpwUWE4ejBYL0F3U1BVL1BhbVFFUFp1dFdjSXRsbEk2aitPNGZtV0kzZWlaZlRBNmh4Sm1ZYUluWk0xYW81bk0vWWlXTUZIN1FvbjNUSERkWmlkYU8vc29YWm1MWjJqZEt3UFc5UWcwMEh0Tmd2S3REcVZyMndnN0JwYTZZQWVIQnJKSU5xalQ4QXNEcU40bmxnRk9lRm1mN21jV3RsT1BCdktDbUxoMXdYNEhJcDhOWkU3bklMYS9YZE1ZS1JOOEZkdzM3UUtGZUwvSzNvZkk1cVN1eGIxcFY5d0tNYVk0UllrL2kxdXhHTHRtWllwdEE3MDlqQzEyUUJNZEU3Nmx6YkVrcmlrdVJ5NG1mRXQxYzNyOEtweDRPVUpsbXBsMGxSSmZxZnlqRDRqdlFQd1Rzc3AyRk12cnBGNkFGWmFvNXFHWm1KOXZrZXZ6UGZVSUoxNGRPd00wMTZuUTdlbVJvZzVLYnFzWCtjeWE2Umtha1pvT05xSHRBbU01RWE4dmdYelA2aEdqSmhFcW0xSGl0d0h3aXNNUUJRTnNVaS9XRWlrMm5JbGFkWWl2R0tob0ZWd2J4OU11WXoweGtpSlB1QVY0M0hxa0dGbm42UlZjbFJRa2JUZElKbDdHamdGZDcxUWM0Ti96MkFqWC9KZUJrUFNKTzlWL0FjTW5ZOWtqYmQ4L0FBQUFBRWxGVGtTdVFtQ0MiLz48L2RlZnM+PC9zdmc+" />
</p>

---

Projeto final da disciplina de Introdução a Algoritmos/Programação, desenvolvido com Python e Pygame.
A proposta é começar com uma base funcional e evoluir o jogo ao longo do semestre.

## Integrantes do grupo

- Davi Emanuel Moreira Sollar
- João Pedro Silva Dantas
- Pedro Henrique Silva Oliveira
- Vinícius Marx Galvão

## Objetivo do jogo

O jogador deve explorar o mapa, interagir com NPCs e resolver desafios para juntar informações da investigação. A partida termina quando o tempo se esgota, quando todas as vítimas são perdidas ou quando os enigmas disponíveis são encerrados.

## Estado atual

A versão atual possui:

- Menu inicial com botões para iniciar ou sair.
- Mapa em tiles com colisão nas bordas.
- Jogador animado, movimentação por teclado e câmera acompanhando o personagem.
- NPC animado com diálogo carregado de arquivo JSON.
- Tela de desafio com carta, campo de resposta e validação simples.
- Contadores de tempo total e tempo por enigma.
- Controle de vítimas vivas, recorde e ranking em arquivos de texto.
- Testes unitários para funções puras de lógica.

## Controles

- `W` ou `↑` (seta para cima): mover para cima.
- `S` ou `↓` (seta para baixo): mover para baixo.
- `A` ou `←` (seta para esquerda): mover para esquerda.
- `D` ou `→` (seta para direita): mover para direita.
- `Shift esquerdo`: correr.
- `Espaço`: avançar diálogos/interagir.
- `Enter`: confirmar nome ou resposta.
- `Mouse`: clicar nos botões, ativar campos de texto e virar a carta do desafio.
- `Esc`: fechar a tela de desafio quando ela estiver aberta.

## Estrutura do projeto

- `main.py`: ponto de entrada da aplicação.
- `requirements.txt`: dependências do projeto (`pygame-ce` e `pytest`).
- `src/`: código-fonte principal do jogo.
- `assets/`: imagens, textos, sons e fontes.
- `data/`: arquivos simples de persistência, como ranking e recorde.
- `docs/`: proposta e documentação de planejamento.
- `tests/`: testes automatizados.

## Como executar o jogo

```bash
git clone LINK_DO_REPOSITORIO
cd NOME_DA_PASTA
pip install -r requirements.txt
python main.py
```

## Como executar os testes

```bash
python -m pytest
```

## Observações

- A proposta original está em `docs/proposta.MD`.
- Os diálogos do NPC atual ficam em `assets/textos/npc.json`.
- O desafio implementado valida a resposta textual `teste`.
- O ranking e o recorde são salvos em `data/ranking.txt` e `data/recorde.txt`.
