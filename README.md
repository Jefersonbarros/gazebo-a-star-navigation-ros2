# gazebo-a-star-navigation-ros2
Ambiente de simulação próprio no Gazebo com implementação de navegação de planejamento de caminho com A* (A-star).

Nesse trabalho utilizei um ambiente de simulação ROS2 e Gazebo Ingnition, empacotado em um contêiner Docker. Disponível neste repositório:  https://github.com/milenafariap/ros2_workshop Navegação com Robô Diferencial em Labirinto 3D com A⁎ https://github.com/tatianambsantos/astar


###  1. Clone o repositório
```bash
git clone https://github.com/tatianambsantos/astar.git
cd astar

```

###  2. No terminal dentro do repositório, crie um ambiente Python

```bash
python3 -m venv venv
source venv/bin/activate

```
Instale dependências:

```bash
pip install matplotlib numpy


```


###  3. Gere o labirinto

```bash
python3 generate_maze.py




```

<img src="Captura de tela de 2025-12-23 21-42-21.png" alt="Texto Alternativo">

###  4. Rodar o A*

```bash
python astar.py



```
<img src="Captura de tela de 2025-12-23 22-23-35.png" alt="Texto Alternativo">
