# motoBot
Descrição do Projeto:

O projeto consiste no desenvolvimento de um bot automatizado para WhatsApp, utilizando **Node.js** e a biblioteca **whatsapp-web.js** como base. O objetivo é criar um sistema que monitora as solicitações de motoboy feitas pelo WhatsApp e, ao identificar um novo pedido, o bot será o primeiro a responder e garantir a corrida. O sistema funcionará de forma contínua e automatizada, permitindo que os motoboys possam capturar as corridas de forma mais ágil e eficiente.

**Como funciona:**
1. O bot, desenvolvido em **Node.js**, ficará constantemente monitorando o WhatsApp, utilizando a API do **whatsapp-web.js** para interceptar e analisar as mensagens recebidas.
2. Quando o bot detectar uma solicitação de motoboy (por meio de palavras-chave ou padrões definidos), ele irá responder automaticamente à solicitação, sinalizando a disponibilidade do motoboy para a corrida.
3. O sistema será configurado para garantir que o motoboy mais próximo ao local da solicitação seja o primeiro a ser notificado e, portanto, o primeiro a pegar a corrida.
4. O bot também pode ser configurado para enviar uma confirmação ao cliente, garantindo que a corrida foi aceita rapidamente, criando uma experiência mais ágil e eficiente para o usuário final.

**Tecnologias Utilizadas:**
- **Node.js**: Para o desenvolvimento do back-end do bot, garantindo performance e escalabilidade.
- **whatsapp-web.js**: Biblioteca que permite integrar o bot ao WhatsApp, possibilitando a leitura e o envio de mensagens de maneira automatizada.
  
**Vantagens do Sistema:**
- **Rapidez e eficiência:** O bot é capaz de identificar rapidamente as solicitações e garantir que o motoboy seja o primeiro a ser notificado.
- **Disponibilidade 24/7:** Como o bot opera de maneira automatizada e contínua, ele está disponível a qualquer momento, garantindo que os motoboys possam pegar as corridas independentemente do horário.
- **Automatização e praticidade:** O bot elimina a necessidade de verificação manual das corridas, proporcionando uma solução prática e ágil tanto para os motoboys quanto para os clientes.
