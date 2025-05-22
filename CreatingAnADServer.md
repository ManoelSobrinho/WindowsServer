# Criando um servidor AD (Domain Controller)

## Configurações necessárias

- Definir um IP fixo (caso não esteja).
- Configurar o DNS.
- Definir o nome da máquina (caso não esteja).

## Procedimento

### 1) Configurações de rede

Server Manager → Local Server → Ethernet

![image](https://github.com/user-attachments/assets/bc13af8b-acf7-4ed5-a76c-951cf9c13106)

Botão direito → Properties → Internet Protocol Version 4 (TCP/IPv4)

![image](https://github.com/user-attachments/assets/43344923-17f6-4a3b-a0ae-dd30db1c2bcb)

![image](https://github.com/user-attachments/assets/8f0be8ab-8a66-455d-a531-c60452900290)

Use the following IP addres → Adicionar configuração de rede

![image](https://github.com/user-attachments/assets/71b4b845-2a92-44c6-bc92-e1078ff03c71)

### 2) Configuração do AD

Server Manager → Dashboard → Add roles and features

![image](https://github.com/user-attachments/assets/37ea2c05-0198-4abb-b968-58926ae738e5)

Next

![image](https://github.com/user-attachments/assets/b402835e-19ed-48d2-8f25-2b948a097043)

Role-based or feature-based installation → Next

![image](https://github.com/user-attachments/assets/b438899b-0e83-4673-9458-e5cc1ccf0084)

Select a server from the server pool → Next

![image](https://github.com/user-attachments/assets/0c11cb81-7657-4004-b0df-24f339f96608)


