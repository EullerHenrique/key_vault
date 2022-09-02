# Azure Key Vault

1. Acesse https://portal.azure.com/

<img width="828" alt="Captura de tela 2022-09-02 093919" src="https://user-images.githubusercontent.com/48317736/188150486-385f0aa8-7d80-432a-b6e4-8538721c1466.png">

2. Digite Grupo De Recursos na barra de pesquisa e o selecione

<img width="830" alt="Captura de tela 2022-09-02 093950" src="https://user-images.githubusercontent.com/48317736/188150585-9cf15f9a-1dac-4e27-8796-47c35008d872.png">

4. Aperte em Criar

<img width="826" alt="Captura de tela 2022-09-02 094300" src="https://user-images.githubusercontent.com/48317736/188150682-6a6750ee-909d-4c09-b502-9ff0779220c4.png">

5. Assinatura -> Ex: Tools Software PAYG
6. Grupo de recursos -> Ex: RG-VAULT-DEMO
7. Região -> Ex: (US) East US 2
8. Aperte Revisar + Criar

<img width="326" alt="Captura de tela 2022-09-02 100058" src="https://user-images.githubusercontent.com/48317736/188151399-542e1ba8-4c37-4ecf-af45-16b1c71b9332.png">

9. Aperte em Criar

<img width="269" alt="Captura de tela 2022-09-02 100153" src="https://user-images.githubusercontent.com/48317736/188151567-9621f47c-ad13-41b8-8334-3644350472e8.png">

10. Aperte em Atualizar

<img width="530" alt="Captura de tela 2022-09-02 100231" src="https://user-images.githubusercontent.com/48317736/188151681-c9c2dcdd-e298-4ea6-ae62-78012a10406b.png">

11. Selecione RG-VAULT-DEMO

<img width="703" alt="Captura de tela 2022-09-02 095319" src="https://user-images.githubusercontent.com/48317736/188150705-94eeb03b-4ea9-45c0-81bf-1508e8169efe.png">

12. Digite Cofres De Chaves na barra de pesquisa e o selecione

<img width="796" alt="Captura de tela 2022-09-02 095445" src="https://user-images.githubusercontent.com/48317736/188150933-8b1f1594-ddff-4ffa-a663-9a8ff964d444.png">

13. Aperte em Criar

<img width="637" alt="Captura de tela 2022-09-02 110613" src="https://user-images.githubusercontent.com/48317736/188167812-2246ffed-56b3-4978-8420-d81436fed43c.png">

14. Assinatura -> Ex: Tools Software PAYG
15. Grupo de recursos ->  RG-VAULT-DEMO
16. Nome do cofre de chaves -> Ex: KV-DEMO-TESTE
17. Região -> Ex: (US) East US 2
18. Dias os cofres excluídos devem ser retidos -> Ex: 90
19. Aperte Revisar + Criar

<img width="345" alt="Captura de tela 2022-09-02 110719" src="https://user-images.githubusercontent.com/48317736/188167829-aa9d6dfa-b73e-4ac4-895f-ea760c8540f8.png">

20. Aperte em Criar

<img width="433" alt="Captura de tela 2022-09-02 111127" src="https://user-images.githubusercontent.com/48317736/188167826-6a6ca3dc-16c8-403c-b874-00b3942b9d0c.png">

<img width="1229" alt="Captura de tela 2022-09-02 112120" src="https://user-images.githubusercontent.com/48317736/188170879-12986939-ea8f-4de4-999a-62d469810217.png">

21. Aperte em Ir para o recurso

<img width="1072" alt="Captura de tela 2022-09-02 112144" src="https://user-images.githubusercontent.com/48317736/188170918-6a5d1975-273e-4b3b-9de5-8cbd9475dded.png">

<img width="1459" alt="Captura de tela 2022-09-02 112211" src="https://user-images.githubusercontent.com/48317736/188171023-74ff9228-8973-4506-8828-31543f2f682b.png">

22. Aperte em Políticas de Acesso

23. Aperte em Adicionar Política de Acesso

<img width="1292" alt="Captura de tela 2022-09-02 112315" src="https://user-images.githubusercontent.com/48317736/188202319-a4f81b7e-1661-4023-996c-5bf9388d6eff.png">

23. Configurar usando o modelo ->  Gerenciamento de Segredos e Chaves
24. Permissões de chave -> Ex: 0
25. Permissões do segredo -> Ex: 2 -> Obter e Listar
26. Permissões de certiifcado -> Ex: 0
27. Selecionar a entidade de segurança -> Ex: Euller Henrique Bandeira Oliveira
28. Clieque em Adicionar

<img width="1458" alt="Captura de tela 2022-09-02 112407" src="https://user-images.githubusercontent.com/48317736/188202317-036835e6-b2a0-4f46-b962-50c742f4593b.png">

28. Clique em Salvar

<img width="837" alt="Captura de tela 2022-09-02 143646" src="https://user-images.githubusercontent.com/48317736/188208170-e1ca5c52-790d-49ee-ae5d-4e0ba42b1706.png">
<img width="834" alt="Captura de tela 2022-09-02 143831" src="https://user-images.githubusercontent.com/48317736/188208251-113077d0-e853-4f97-afdd-1e1c0226eb5d.png">

29. Aperte em IAM (Controle de acesso)

<img width="613" alt="Captura de tela 2022-09-02 141518" src="https://user-images.githubusercontent.com/48317736/188210283-431db8c5-33bf-475f-a4b9-26fdb1cf749c.png">

30. Aperte em Adicionar Atribuição De Função

<img width="743" alt="Captura de tela 2022-09-02 141912" src="https://user-images.githubusercontent.com/48317736/188210845-07f9c28c-e1dc-4501-b455-5f43f2137b0f.png">

31. Aperte em Administrador de Cofre de Chaves

<img width="743" alt="Captura de tela 2022-09-02 141912" src="https://user-images.githubusercontent.com/48317736/188210845-07f9c28c-e1dc-4501-b455-5f43f2137b0f.png">

32. Selecionar membros -> Ex: Euller Henrique Bandeira Oliveira

<img width="836" alt="Captura de tela 2022-09-02 142030" src="https://user-images.githubusercontent.com/48317736/188210905-b51c94bd-16b5-4682-a117-08f4e5d984f1.png">

33. Aperte em Examinar + atribuir

<img width="527" alt="Captura de tela 2022-09-02 142517" src="https://user-images.githubusercontent.com/48317736/188211429-3851e1bd-da1c-4cec-83a3-63d02a9f6588.png">

34. Aperte em Examinar + atribuir

<img width="452" alt="Captura de tela 2022-09-02 142532" src="https://user-images.githubusercontent.com/48317736/188211521-99031ac2-ac64-4516-a79b-2b744ea71e7b.png">



                                                 


