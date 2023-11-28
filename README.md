# desafio-pb-aws-react-rachelsaronne
desafio-pb aws react
## **Funcionalidades obrigatórias**

### Gerais

- Fidelidade de cores e tamanho de acordo com o Figma
- Responsividade para telas de até 320px

### **1º Tela** 
Ao clicar no botão Let’s go o usuário deve ser direcionado para a segunda tela do Fluxo.

### **2º Tela** 
- Ao clicar no botão **Back to Home** o usuário deve ser redirecionado novamente para a primeira tela do Fluxo.
- Ao clicar no botão **Fill out the form**, deve ser direcionado para a terceira tela do Fluxo.

### **3º Tela** 
- - Ao clicar no **input de select**, deve aparecer uma lista de opções ao usuário. O conteúdo das opções da lista fica a critério do(da) bolsista.
- Nos **inputs de Radio**, apenas um deles deve ser selecionado. Ou seja, ao clicar em um novo input, o anterior deve ser desmarcado.
- Ao clicar no botão de **Back** o usuário deve retornar a segunda tela do fluxo.
- Ao clicar no botão de **Next** o usuário deve ser direcionado para a quarta tela do fluxo. Contudo, ele só pode ser direcionado se o **input de Radio e Select** estiverem marcados.
- Ao clicar no botão de **Skip** o usuário deve ser direcionado para a quarta tela do Fluxo, podendo ir para ela sem ter selecionado o **input de Radio** ou o de **Select.**
- 
- ### **4º Tela**
- - Ao clicar no **input de select**, deve aparecer uma lista de opções ao usuário. O conteúdo das opções da lista fica a critério do(da) bolsista.
- Na parte com checkboxes, pode ser selecionado um ou mais de um **inputs de Checkbox.**
- Ao clicar no botão de **Back** o usuário deve retornar para a terceira tela do fluxo.
- Ao clicar no botão de **Next** o usuário deve ser direcionado para a quinta tela do fluxo. Contudo, ele só pode ser direcionado se o **input de Checkbox** estiver selecionado.
- Ao clicar no botão de **Skip** o usuário deve ser direcionado para a quinta tela do Fluxo, podendo não ter selecionado algum **input Checkbox.**

   ### **5º Tela**
  - O **TextArea** deve ter no máximo 130 caracteres.
- Ao clicar no botão de **Back** o usuário deve retornar para a quarta tela do fluxo.
- Ao clicar no botão de **Next** o usuário deve ser direcionado para a sexta tela do fluxo. Contudo, ele só pode ser direcionado se **TextArea** conter qualquer tipo de conteúdo.
- Ao clicar no botão de **Skip** o usuário deve ser direcionado para a sexta tela do fluxo, podendo não ter conteúdo no **TextArea.**

- ### **6º Tela**
- - Os **três inputs são obrigatórios** e devem possuir validação HTML.
- Ao clicar no botão de **Back** o usuário deve retornar para a quinta tela do fluxo.
- Ao clicar no botão de **Submit** o cadastro é finalizado com sucesso, e retorna para a primeira tela do fluxo, apenas se os inputs estiverem preenchidos.

## **Funcionalidade Adicionais (NÃO OBRIGATÓRIAS)**

- **Validação dos inputs** com JavaScript.
- Armazenamento dos dados de usuário em **localStorage.**
- Sinalização do numero de caracteres restantes do **TextArea.**
- Utilização de **TypeScript.**
- Criação de uma tela de sucesso, sinalizando que o cadastro foi finalizado com sucesso.
- Responsividade para telas de até 280px
  
