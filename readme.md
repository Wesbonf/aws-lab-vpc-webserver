# ☁️ AWS Academy – Criando uma VPC e Executando um Servidor Web

---

## 🧠 Objetivos do Laboratório

- Criar uma **Amazon VPC personalizada**.  
- Configurar **sub-redes públicas e privadas** em múltiplas zonas de disponibilidade.  
- Criar e associar **tabelas de rotas**, **Internet Gateway** e **NAT Gateway**.  
- Criar um **grupo de segurança (Security Group)** permitindo tráfego HTTP.  
- Executar uma **instância EC2** configurada automaticamente para atuar como **servidor web Apache**.  

---

## 🌐 Criação da VPC e Sub-redes

Foi criada a VPC `lab-vpc` com **IPv4 CIDR Block: 10.0.0.0/16** e as seguintes sub-redes:

- **Sub-rede pública:** `10.0.0.0/24` → 256 endereços  
- **Sub-rede privada:** `10.0.1.0/24` → 256 endereços

Essa configuração permite **isolamento entre recursos públicos e privados** e prepara a VPC para futuras expansões.



![VPC](./images/1.png)
![VPC](./images/2.png)

---
## 🗺️ Mapa de Recursos
Diagrama resumido mostrando a **VPC, sub-redes públicas e privadas, Internet Gateway e instância EC2** do laboratório.

![Mapa de recursos](./images/3.png)
