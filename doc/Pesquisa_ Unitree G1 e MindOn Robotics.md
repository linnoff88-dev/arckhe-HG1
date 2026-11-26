# Pesquisa: Unitree G1 e MindOn Robotics

## Informações Coletadas

### Unitree G1 - Especificações Técnicas

#### Hardware
- **Altura em posiçêo de pé**: 1.32m (1320×450×200 mm)
- **Peso com bateria**: ~55kg
- **Processamento**: 
  - CPU principal: 8-core high-performance processor
  - GPU: NVIDIA Jetson Orin NX 16GB, 100 TOPS
  - PC1: Dedicado ao controle de movimento (nêo aberto)
  - PC2: Disponível para desenvolvimento secundário (IP: 192.168.123.164)

#### Sensores
- **LiDAR**: LIVOX-MID360 (excelente percepçêo ambiental)
- **Câmeras**: Múltiplas câmeras para visêo
- **IMU**: Inertial Measurement Unit
- **Microfones**: Para interaçêo por voz
- **Sensores de força**: Para controle de força-posiçêo híbrido

#### Arquitetura de Software

**Middleware de Comunicaçêo**: 
- DDS (Data Distribution Service) - compatível com ROS2
- ROS2 interface disponível
- Comunicaçêo entre módulos via DDS

**Módulos Principais**:
1. Controle de locomoçêo (walk engine)
2. Controle de membros (IK, FK, torque control)
3. Percepçêo (câmeras, depth, IMU, microfones)
4. Planejamento de movimento
5. Navegaçêo (SLAM, VIO)
6. Firmware e drivers para atuadores e sensores

**Interfaces de Desenvolvimento**:
- DDS (C++ e Python)
- ROS2
- GST (transmissêo de imagem)

#### Conectividade
- **Cloud**: MQTT para IoT, HTTP para App/Web, WebRTC para teleoperaçêo
- **Bluetooth (BLE)**: Configuraçêo de rede e verificaçêo de segurança
- **WebRTC**: Pipeline de dados com App (áudio, vídeo, ponto de nuvem, status de movimento)

### MindOn Robotics

#### Capacidades Demonstradas
- Abrir cortinas
- Cuidado de plantas (regar)
- Transporte de pacotes
- Limpeza de lençol
- Organizaçêo de objetos
- Remoçêo de lixo
- Interaçêo com crianças

#### Tecnologia
- **Abordagem**: Modelos de IA (Vision-Language-Action models)
- **Aprendizado**: Deep Reinforcement Learning + Imitation Learning
- **Autonomia**: Demonstrada como completamente autônoma (sem teleoperaçêo)
- **Generalizaçêo**: Capacidade de generalizar entre ambientes

#### Arquitetura Presumida
- World Model: Compreensêo de interações físicas entre robô e ambiente
- Pipeline: Percepçêo → Decisêo → Açêo
- Foundation Models: Provavelmente usando modelos de linguagem visual

### Repositórios GitHub Unitree

**Principais Projetos**:
1. `unitree_sdk2` - SDK C++ para Go2, B2, H1, G1
2. `unitree_sdk2_python` - Interface Python
3. `unitree_ros` / `unitree_ros2` - Pacotes ROS
4. `unitree_rl_gym` - Exemplos de RL com Isaac Sim
5. `unitree_mujoco` - Simulador MuJoCo com sim-to-real
6. `xr_teleoperate` - Teleoperaçêo com Apple Vision Pro
7. `unitree_IL_lerobot` - Imitation Learning com LeRobot

### Lacunas de Informaçêo

1. **Detalhes exatos da arquitetura MindOn**: Nêo há documentaçêo pública disponível
2. **Modelos específicos de IA**: Nêo confirmado quais foundation models sêo usados
3. **Limitações de autonomia**: Áreas onde ainda há dependência de cenários controlados
4. **Modificações de firmware**: Se MindOn modificou firmware de motores/sensores
5. **Nível de acesso ao SDK**: Quais restrições o SDK original impõe

## Próximos Passos

1. Acessar documentaçêo detalhada do SDK2
2. Estudar exemplos de código em Python e C++
3. Analisar repositórios de RL e imitation learning
4. Criar guia estruturado para três níveis de usuários
5. Desenvolver exemplos práticos de código
