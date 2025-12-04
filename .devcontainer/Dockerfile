FROM ros:humble-desktop

# Instalar dependências
RUN apt-get update && apt-get install -y \
    python3-colcon-common-extensions \
    ros-humble-xacro \
    ros-humble-urdf-tutorial \
    git \
    nano \
    && rm -rf /var/lib/apt/lists/*

# Workspace padrão
WORKDIR /scara_ws
