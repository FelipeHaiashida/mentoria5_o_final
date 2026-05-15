# Museu da Computação
Um museu virtual em Realidade Virtual (VR) feito em Unity, onde o visitante pode explorar três marcos da história da computação representados por três máquinas diferentes ao longo do tempo.

## Demonstração

> 📹 **Vídeo de demonstração — execução na máquina local**

<!-- Substitua o link abaixo pelo URL do seu vídeo (YouTube, Google Drive, etc.) -->
[![Demonstração do Museu da Computação](https://img.shields.io/badge/▶%20Assistir%20demonstração-blue?style=for-the-badge)](URL_DO_VIDEO_AQUI)

<!-- Se preferir incorporar diretamente um vídeo do YouTube, use o bloco abaixo no lugar do badge acima:
[![Demonstração do Museu da Computação](https://img.youtube.com/vi/ID_DO_VIDEO/maxresdefault.jpg)](https://www.youtube.com/watch?v=ID_DO_VIDEO)
-->

---

## Sobre o projeto
O projeto apresenta uma cena única ([Museu da Computação.unity](Assets/Scenes/Museu%20da%20Computa%C3%A7%C3%A3o.unity)) onde o usuário percorre um ambiente expositivo com três computadores em ordem cronológica:
1. **Computador de Terminal** — representa a era dos primeiros computadores, com interface por linha de comando e terminais conectados a unidades centrais.
2. **PC de Mesa** — representa a popularização da computação pessoal, com gabinete, monitor e periféricos típicos do desktop doméstico/comercial.
3. **Notebook Moderno** — representa a computação portátil atual, compacta e integrada.

## Tecnologias
- **Unity** 6000.3.15f1
- **XR / Oculus** — projeto preparado para execução em headset VR (ver [Assets/Oculus](Assets/Oculus) e [Assets/XR](Assets/XR))
- **New Input System** — controles definidos em [InputSystem_Actions.inputactions](Assets/InputSystem_Actions.inputactions)

## Estrutura do projeto
```
Assets/
├── Scenes/              # Cena principal do museu
├── Modelos 3D/          # Modelos dos computadores e mobiliário
│   ├── computer-terminal/   # (1) Computador de terminal
│   ├── pvbhu3eel4hs-CPU/    # (2) PC de mesa
│   ├── laptop/              # (3) Notebook moderno
│   └── table-sofa/          # Mobiliário do ambiente
├── Materials/           # Materiais
├── Texture/             # Texturas
├── SkySeries Freebie/   # Skybox do ambiente
├── Oculus / XR/         # Configuração do VR
└── Settings/            # Render pipeline e configurações
```

## Como executar
1. Abrir o projeto no Unity **6000.3.15f1**.
2. Abrir a cena `Assets/Scenes/Museu da Computação.unity`.
3. Conectar um headset compatível (Oculus/Meta Quest) ou usar o modo Play do Editor.
4. Pressionar **Play** para iniciar a visita.
