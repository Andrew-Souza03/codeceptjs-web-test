# Codeceptjs - Automação de Testes Web

- 📌 Este projeto faz parte do meu aprndizado na Formação Agile Test Engineer na escola [E2ETreinamentos](https://e2etreinamentos.com.br/)

- 💻 Para os testes realizados usamos o site [http://teststore.automationtesting.co.uk/](http://teststore.automationtesting.co.uk/) , que é um e-commerce fictício.


##  👨🏻‍💻Tecnologias Utilizadas
- [Codeceptjs](https://codecept.io/quickstart/) - Framework de testes automatizados.
-  [Playwright](https://codecept.io/helpers/Playwright/#playwright) - Helper usado no projeto.
- [Node.js](https://nodejs.org/en/) - Plataforma de desenvolvimento
- [Mochawesome](https://codecept.io/reports/#html) - Reports de execução de testes em HTML.

#### 🎨 Padrão de design do projeto:
-   **Modelo de objeto de página** (por meio **Page Object** )


## 🧪 Suítes de Teste:
Os testes funcionais foram distribuidos nas seguintes suítes:

   |  Login                                        |   Teste     |                          
   |-----------------------------------------------|-------------|
   |CT01- deve realizar login com sucesso                |`'Positivo'` |
   |CT02- não deve realizar login com email inválido     |`'Negativo'` |
   |CT03- não deve realizar login com senha inválida      |`'Negativo'` |

 
   
## 🚀 Como executar o projeto
Essas instruções permitiração que você obtenha uma cópia do projeto  sua máquina local para fins de teste.

Clonar o projeto:
```
git clone https://github.com/repoe2e/codecept-web-test.git
```

Execute o comando abaixo:
```
git remote add origin https://github.com/repoe2e/codecept-web-test.git
```

### 🤖 Execute o comando abaixo para instalar das dependências do projeto:
```
npm install
npm install --save-dev playwright
npm i codeceptjs --save-dev
npm i mochawesome mocha -D
```
### ⚙️Execute o comando abaixo para rodar os testes via linha de comando:

Execute o comando abaixo para rodar os testes:
```
npx codeceptjs run 
```
Execute o comando abaixo para rodar os testes por tags:
```
npx codeceptjs run --grep "nomeDaTag"
```
Execute o comando para rodar os testes e obter relatórios:
```
codeceptjs run --reporter mochawesome
```

## 📌 Notas Gerais
 ---
#BoraEstudar!
 
Feito com ❤️ por [Andrew Souza](https://github.com/Andrew-Souza03) 😊
⌨️ Me contate pelo [LinkedIn](https://www.linkedin.com/in/andrew-eduardo-569a28187/) 😊
