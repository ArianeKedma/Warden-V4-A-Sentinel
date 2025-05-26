# Warden V4 A Sentinel -  Monitoramento e Vigilância em Tempo Real

# Índice

- [Sobre a CyberSolutions](#sobre)
- [Warden](#warden)
- [Objetivo](#objetivo)
- [Tecnologias](#tecnologiasUtilizadas)
- [Instalação e Uso](#InstalaçãoeUso)
- [Configuração](#configuração)
- [Contato](#contato)

# Sobre 

Somos uma empresa de segurança especializada em IoT, oferecendo soluções inteligentes e inovadoras para proteger pessoas e patrimônios. 
Unimos tecnologia de ponta e automação para transformar a segurança tradicional em um sistema moderno, conectado e eficiente.

---

# Warden 

O Warden é um drone de segurança avançado, ideal para grandes eventos e locais críticos. Com IA embarcada, visão noturna em HD, sensores térmicos, GPS com geofencing e conectividade 4G/5G, 
oferece patrulhamento aéreo autônomo ou manual, detecção de movimentos suspeitos, transmissão ao vivo e envio de alertas em tempo real. 
Ele cobre áreas onde câmeras fixas não alcançam, elevando a segurança a outro nível.

---

# 🎯 Objetivo

- Reduzir a criminalidade e prevenir invasões em áreas públicas.
- Monitorar eventos de grande porte, com segurança e eficiência.
- Facilitar o patrulhamento de regiões de díficil acesso.
- Fornecer dados estratégicos em tempo real.

---

# ⚙️ Tecnologias Utilizadas

💻 Software
- Python/C++: Controle e programação embarcada.
- MQTT / WebSocket: Comunicação segura entre drones e central.
- LiDAR SDK: navegação e mapeamento 3D.
- TensorFlow Lite/ OpenCV: Processamento e análise de imagens em tempo real.

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="40" />
</p>

⌨️ Hardware
- Câmeras 360º HD e térmicas
- Sensores LiDAR para navegação 3D
- Microfones direcionais
- Sistema de recarga automática (pouso assistido)

---

# Instalação e Uso

Passos para executar o projeto

- Requisitos:
- Hardware de drone compatível com SDK de controle autônomo.
- Computador ou servidor para central de comando.
- Sistema operacional Linux ou Windows (recomendado: Ubuntu 22.04).
- Docker e Docker Compose instalados.

👣 Passos:

1. **Clone o repositório**:
 
```
git clone https://github.com/ArianeKedma/Warden-V4-A-Sentinel
```

2. **Configure as variáveis de ambiente**:

```
COMM_KEY=suachavedecomunicacao
DRONE_ID=seuid
ROUTES=config/routes.json
```

3. **Inicie os serviços**:

```
docker-compose up -d
```

4. **Configure o drone**:

```
./scripts/upload_firmware.sh
```

---

# Configuração

---

# Contato

- Equipe:
- [Ariane Kedma Costa da Silva](https://github.com/ArianeKedma)
- [Julia de França Macena Silva](https://github.com/Macenaaa)
- [Lavínia Domingos](https://github.com/laviDomingos)
