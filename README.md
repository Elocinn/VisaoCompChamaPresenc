# Sistema de Controle de Presença Acadêmica
Este projeto visa desenvolver um **sistema de controle de presença** para ambientes acadêmicos utilizando técnicas de **visão computacional** e **reconhecimento facial**. O objetivo é **automatizar e modernizar** o sistema tradicional de chamada, atualmente feito manualmente ou com lista de presença. 
### Visão Geral
O sistema realiza a captura de imagens em tempo real através de câmeras estrategicamente posicionadas para identificar os alunos presentes e registrar suas presenças em um banco de dados. Esse processo visa ser **intuitivo e fácil de usar**, tanto para alunos quanto para professores, contribuindo para um ambiente de aprendizado mais moderno e eficiente.
### Tecnologias Utilizadas
- **Linguagem**: Python
  - **OpenCV**
  - **Face Recognition**
- **Banco de Dados**
### Funcionamento
Cada aluno possui um **identificador único** associado à sua face, o que permite a rápida atualização dos dados de presença a cada nova detecção. A identificação é feita ao comparar os embeddings faciais extraídos das imagens com um banco de dados de rostos dos alunos.
### Possível Expansão
Caso necessário, uma **interface web** simples e flexível pode ser implementada utilizando o **framework Flask** da linguagem Python, permitindo a visualização e gerenciamento dos dados de presença.
---
**Resumo**: Este sistema busca simplificar e modernizar o controle de presença em ambientes acadêmicos, utilizando o que há de mais avançado em tecnologias de visão computacional e reconhecimento facial.
