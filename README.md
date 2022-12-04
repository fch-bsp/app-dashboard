# Criação de uma aplicação que vai gerenciar o acesso ao cluster do k8s --> app-dashboard

---

![Captura de tela de 2022-12-04 09-19-01](https://user-images.githubusercontent.com/102867453/205490006-e4f8a8bb-52f8-4dd8-94f5-c65e35c05bdb.png)

---
## Negar - Acesso: "Forbidden"

![Captura de tela de 2022-12-04 09-23-37](https://user-images.githubusercontent.com/102867453/205490220-c1a20703-c438-428a-98ed-e409955ca030.png)

#### Entendimento sobre ServiceAccount
![Captura de tela de 2022-12-04 10-59-43](https://user-images.githubusercontent.com/102867453/205494832-8c16154e-08e7-465f-ac10-4aee5f9f517c.png)

![Captura de tela de 2022-12-04 11-01-37](https://user-images.githubusercontent.com/102867453/205494940-64d4bc7d-027a-48b9-bb64-0dc84a262989.png)


#### Criação do ServiceAccount 


![Captura de tela de 2022-12-04 10-58-01](https://user-images.githubusercontent.com/102867453/205494740-af12961d-c68d-4b6b-b850-65ffa98190aa.png)


---

#### Acesso aos Pods:

![Captura de tela de 2022-12-04 10-45-47](https://user-images.githubusercontent.com/102867453/205494195-bed42f82-f00a-4062-9ef4-a49aceb80a3e.png)

#### Acesso aos Services:
![Captura de tela de 2022-12-04 10-51-18](https://user-images.githubusercontent.com/102867453/205494412-9f202c06-6e06-4155-9d95-173c6d441d8b.png)

#### Acesso: "Forbidden" no Deployment:

![Captura de tela de 2022-12-04 09-23-37](https://user-images.githubusercontent.com/102867453/205490220-c1a20703-c438-428a-98ed-e409955ca030.png)

#### Manifesto habilitando Deployment 

![Captura de tela de 2022-12-04 10-54-24](https://user-images.githubusercontent.com/102867453/205494572-83c6e60e-17e1-46b5-ace9-f7e620666030.png)


#### Acesso aos Deployment:

![Captura de tela de 2022-12-04 10-55-52](https://user-images.githubusercontent.com/102867453/205494649-84a8ee79-0de7-466f-8c77-e997b61ad7fb.png)




## Criação do arquivos de manifesto para o acesso ao cluster:



### RBCA --> Role-Based Access Control 
### ServiceAccount


-----

![Captura de tela de 2022-12-03 13-33-22](https://user-images.githubusercontent.com/102867453/205490168-3b6584f3-6a4b-4a28-bd99-28754a88e8d6.png)
