# Criando-sistema-de-reconhecimento-facial
Este projeto utiliza a biblioteca DeepFace para realizar reconhecimento facial entre duas imagens.
## Tecnologias Utilizadas
DeepFace: Biblioteca de reconhecimento facial.
- TensorFlow: Framework de aprendizado de máquina para construção de modelos.
- OpenCV: Biblioteca para processamento de imagens.
## Como Usar
### Instale as dependências:
- pip install deepface
### Execute o código para verificar duas imagens:
- from deepface import DeepFace
result = DeepFace.verify("imagem1.jpg", "imagem2.jpg")
print(result)
