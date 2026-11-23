# Soccer Fingers 2D

Jogo de futebol 2D em **computação gráfica**, feito em Python com **OpenGL**. Tem campo, times com formações, bola, jogadores e placar.

A versão 3D está em [Soccer-Fingers-3D](https://github.com/MayronnGomes/Soccer-Fingers-3D).

<!-- Adicione aqui um print ou GIF do jogo em docs/ e referencie: ![Jogo](docs/jogo.gif) -->

## Tecnologias

Python · PyOpenGL (GLUT) · PyGLM · NumPy · Pillow

## O que há no código

- `Game` com laço de jogo, temporizador de quadros, teclado e mouse.
- `Campo`, `Bola`, `Jogador`, `Time`, `Formation` e `Placar`.
- Primitivas geométricas (`Cube`, `Triangule`, `Circle`).
- Texturas do campo, da bola, do gol e da trave.

## Como rodar

Requisito: Python 3.12.

```bash
pip install PyOpenGL PyGLM numpy pillow
python TrabalhoCG_2D.py
```

## Autor

Mayronn Gomes Viana. Projeto de computação gráfica desenvolvido durante a graduação na UFC.
