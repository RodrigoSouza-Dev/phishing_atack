#Phishing em Cibersegurança

#O que é Phishing?
Phishing é uma técnica de engenharia social utilizada por cibercriminosos para enganar pessoas e obter informações sensíveis, como credenciais de login, números de cartão de crédito ou outros dados pessoais. Os atacantes geralmente se passam por instituições confiáveis, como bancos ou redes sociais, enviando e-mails, mensagens ou criando páginas falsas para convencer as vítimas a fornecerem suas informações.

#Como Funciona?
O ataque de phishing normalmente envolve:
Criação de um site falso que se parece com uma página legítima (como a página de login do Facebook ou de um banco).
Envio de e-mails ou mensagens fraudulentas para as vítimas, contendo links para o site falso.
Quando a vítima insere seus dados, eles são enviados diretamente para o atacante, ao invés de para o site legítimo.
Simulação de Phishing com Kali Linux
No Kali Linux, uma das ferramentas mais populares para simular ataques de phishing é o Social Engineering Toolkit (SET). Essa ferramenta permite que os usuários criem páginas falsas de login que se assemelham a sites reais. IMPORTANTE: A utilização desta técnica fora de um ambiente controlado e autorizado é ilegal e antiética.

#Exemplo de uso do SET para Phishing:
Instalar o SET: O SET já vem pré-instalado no Kali Linux, mas caso precise, use o comando:

bash
Copiar código
sudo apt-get install set
Rodar o SET: Abra o terminal e digite:

bash
Copiar código
sudo setoolkit

#Configuração: No menu do SET, selecione as seguintes opções:
1) Social-Engineering Attacks
2) Website Attack Vectors
3) Credential Harvester Attack Method
2) Site Cloner
Inserir URL: Insira o URL do site que deseja clonar (ex: https://www.facebook.com), e o SET irá clonar a página e configurá-la para coletar as credenciais inseridas.

Acessar via IP: A ferramenta configurará um servidor local. Envie o IP do seu Kali Linux para a vítima, e ela será redirecionada para a página clonada.

#Observações:
Ambiente Controlado: Essas atividades devem ser feitas exclusivamente em ambientes controlados para fins educacionais ou de testes de segurança com permissão.
Legalidade: O uso de phishing fora desses ambientes é crime e pode resultar em sérias penalidades legais.

#Requisitos
Kali Linux
Social Engineering Toolkit (SET)


