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

### 2) Adição das features

Server Manager → Dashboard → Add roles and features

![image](https://github.com/user-attachments/assets/37ea2c05-0198-4abb-b968-58926ae738e5)

Next

![image](https://github.com/user-attachments/assets/b402835e-19ed-48d2-8f25-2b948a097043)

Role-based or feature-based installation → Next

![image](https://github.com/user-attachments/assets/b438899b-0e83-4673-9458-e5cc1ccf0084)

Select a server from the server pool → Next

![image](https://github.com/user-attachments/assets/0c11cb81-7657-4004-b0df-24f339f96608)

Marcar a opção: Active Directory Domain Services

![image](https://github.com/user-attachments/assets/42e9f694-bbb0-4740-9396-3b241d0dfbda)

Marcar a opção: Add features

![image](https://github.com/user-attachments/assets/45057439-eabe-4d2e-adb3-8b0df408986d)

Next

![image](https://github.com/user-attachments/assets/942cb6a5-3644-4ebc-9187-48b0e613b35c)

Next

![image](https://github.com/user-attachments/assets/9933149b-9308-412e-ac1d-b0973b47533a)

Next

![image](https://github.com/user-attachments/assets/1d199153-2f60-40c8-b130-3e8fea1a5301)

Marcar a opção: Restart the destination server automatically if required → Yes → Install

![image](https://github.com/user-attachments/assets/ad2e746b-3518-4bca-bbfa-66c52a9cd42b)

Close

![image](https://github.com/user-attachments/assets/67b6ea86-108a-4766-915c-8569ac0f2631)

### 3) Promover servidor como Domain Controller

Server Manager → Dashboard → Notifications → Promote this server to a domain controller

![image](https://github.com/user-attachments/assets/0d64f542-6fcb-4772-ba34-7b6ce6290be7)

Add a new forest → Next → Especificar Root domain name

![image](https://github.com/user-attachments/assets/6bef7bed-7bd2-4b63-92da-29ab43ba57f5)

Inserir senha do DSRM → Next

![image](https://github.com/user-attachments/assets/6c19c22c-fa61-454b-b07d-62383c46ce77)

Next

![image](https://github.com/user-attachments/assets/7920b1b3-c273-4b57-94ad-b4a3d0f27569)

Next

![image](https://github.com/user-attachments/assets/6da3b271-4c37-4356-a9e1-474b703acc5d)

Next

![image](https://github.com/user-attachments/assets/de6b95dd-9ac1-4aee-8c28-17947c6be11f)

Next

![image](https://github.com/user-attachments/assets/ef37aa80-77e0-4c73-ac1c-b9dd5b8dd729)

Install

![image](https://github.com/user-attachments/assets/2687c5e6-944f-4f2d-9fe5-b930929b32eb)
