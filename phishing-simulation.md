# Phishing para Captura de Senhas do Facebook
Neste projeto, o objetivo é simular um ataque de phishing com o propósito educacional, utilizando ferramentas avançadas de segurança disponíveis no Kali Linux. 
A simulação envolve a clonagem de um site legítimo (neste caso, o Facebook) para demonstrar como credenciais podem ser capturadas em um ambiente controlado, permitindo que profissionais de segurança entendam a dinâmica por trás desse tipo de ataque e desenvolvam defesas eficazes contra ele.

# Ferramentas Utilizadas:
Kali Linux: Sistema operacional amplamente utilizado para testes de segurança.
SET Toolkit (Social Engineering Toolkit): Ferramenta poderosa para executar ataques de engenharia social e coleta de informações.

1. Torne-se superusuário
sudo su

2. Inicie o SET Toolkit
setoolkit

3. Escolha "Social-Engineering Attacks"
- Navegue no menu e insira o número correspondente:
1

4. Escolha "Website Attack Vectors"
- Navegue no menu e insira o número correspondente:
2

5. Escolha "Credential Harvester Attack Method"
- Navegue no menu e insira o número correspondente:
3

6. Escolha "Site Cloner"
- Navegue no menu e insira o número correspondente:
2

7. Configure o endereço IP local
- Use o comando abaixo em outro terminal para encontrar o IP da máquina:
ifconfig
- Insira o endereço IP exibido (exemplo: 192.168.0.105)

8. Insira a URL para clonagem
- Exemplo:
http://www.facebook.com

- O SET Toolkit agora configurará o site clonado e capturará as credenciais inseridas.
