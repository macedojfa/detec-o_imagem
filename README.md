# detec-o_imagem
🔍 Sistema de Detecção de Armas com Visão Computacional

Aluno: Rodrigo Bento de Macedo
Curso: Desenvolvimento em Python

---
📜 Sobre o Projeto

Este projeto foi desenvolvido em Python e tem como objetivo aplicar visão computacional para detecção de objetos voltada à segurança, com foco em identificar armas de fogo em imagens ou vídeos.

A aplicação utiliza modelos de inteligência artificial YOLO para realizar a detecção em tempo real, podendo ser aplicada em sistemas de vigilância, monitoramento de ambientes e apoio à segurança pública.
---

✨ Funcionalidade Principal

A principal funcionalidade do sistema é identificar armas em imagens ou transmissões de vídeo, desenhando caixas delimitadoras e exibindo o nível de confiança da predição.

O projeto pode ser utilizado tanto com vídeos locais (.mp4) quanto com câmeras em tempo real.

---
🚀 Instalações Necessárias

Para configurar o ambiente e executar o projeto, siga os passos abaixo:
```bash
# Crie um ambiente virtual (opcional, mas recomendado)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Instale as dependências principais
pip install ultralytics opencv-python
```
---

⬇️ Pré-requisitos

Certifique-se de possuir:

Python 3.12.5

Ultralytics (YOLO11)

OpenCV (cv2)

---

🏁 Como Executar o Projeto

Coloque o arquivo de vídeo (por exemplo, aracruz.mp4) e o modelo treinado (best_TCC.pt) na mesma pasta do script.

1.Execute o código Python:
```bash
python armas.py
```
2.A janela exibirá o vídeo com as detecções destacadas em tempo real.

3.Pressione ESC para encerrar a execução.

---

🎨 Tecnologias Utilizadas

Python 3.12.5

Ultralytics YOLO11

OpenCV

---

📃 Licença

Este é um projeto acadêmico, desenvolvido com fins educacionais e demonstração de tecnologia de visão computacional aplicada à segurança.

---

> Desenvolvido por Rodrigo Bento de Macedo — 2025