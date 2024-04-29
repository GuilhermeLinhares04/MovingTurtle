# MovingTurtle

Este repositório contém um projeto em ROS 2 que utiliza o turtlesim para fazer um desenho com uma tartaruga.

## Requisitos

Para executar este projeto, é necessário ter o ROS 2 instalado e o linux como sistema operacional.
Além disso, é necessário clonar o repositório [ros2_tutorials](https://github.com/ros/ros_tutorials.git) no caminho `turtle_workspace/src`. Para isso, execute o comando abaixo:

```bash
git clone https://github.com/ros/ros_tutorials.git -b humble 
```

## Como executar

Para executar o projeto, siga os passos abaixo:

1. Clone este repositório
2. Abra um terminal e navegue até a pasta _turtle_workspace_ utilizando o comando `cd <caminho>/turtle_workspace`
3. Execute o comando `colcon build`, para compilar o projeto
4. Execute o comando `source install/setup.bash`, para carregar as variáveis de ambiente
5. Execute o comando `ros2 run turtle_pond turtle`, para executar o projeto

## Vídeo de demonstração

Clique na imagem abaixo para assistir ao vídeo de demonstração do projeto:

[![Vídeo de demonstração](https://arminlab.com/wp-content/uploads/2022/09/icons8-youtube-play-button-2048-300x300.png)](https://youtu.be/dS2lNNI1Y84)