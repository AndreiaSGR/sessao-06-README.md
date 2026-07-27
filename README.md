# sessao-06-README.md 
- Desafio Prático Integrador — Mini-CTF Defensivo Linux
## 1. Identificação

### Portas encontradas

<img width="635" height="195" alt="Captura de ecrã 2026-07-27 183650" src="https://github.com/user-attachments/assets/cd3814ad-b4b2-4af3-904e-3f20f5d19e47" />

Não foi possivel verificar as portas sendo que o servidor não tinha conexão a internet para correr o nmap.
### Contas analisadas
Não foram encontradas contas sem password.
Foi analisado o ficheiro authorized_keys para confirmar a existência de chaves públicas, encontrando as seguintes:

<img width="882" height="427" alt="image" src="https://github.com/user-attachments/assets/4471eb82-801d-40fc-942e-0241cfc7d037" />

## 2. Contenção

Foi ativada a firewall UFW.

<img width="685" height="250" alt="Captura de ecrã 2026-07-27 190812" src="https://github.com/user-attachments/assets/0a1aded8-b836-4b68-9745-135cbf8adefc" />

Foi ativada a firewall UFW com uma política de segurança restritiva. Todas as ligações de entrada foram bloqueadas por defeito (deny incoming), sendo permitida apenas a porta 22/TCP, necessária para acesso remoto via SSH. As ligações de saída permaneceram autorizadas (allow outgoing) e o registo de eventos (logging) ficou ativo.
## 3. Remediação
Não foi possivel verificar as configurações do SSH sendo que o servidor não tinha conexão a internet e nem download do lynis para auditoria do sistema.
