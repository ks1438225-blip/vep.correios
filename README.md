Consulta de CEP

Este é um projeto simples em HTML, CSS e JavaScript que permite ao usuário consultar informações de um CEP utilizando a API pública do ViaCEP.

Além disso, o projeto possui integração com Firebase Realtime Database para salvar o último CEP consultado.

🚀 Funcionalidades

🔎 Consulta de CEP digitado pelo usuário

📡 Consumo da API ViaCEP

💾 Salvamento do CEP no Firebase

✅ Validação de CEP (8 dígitos obrigatórios)

⚠️ Tratamento de erros (CEP inválido ou não encontrado)

🛠️ Tecnologias Utilizadas

HTML5

CSS3

JavaScript

API pública do ViaCEP

Firebase Realtime Database

📂 Estrutura do Projeto
📁 projeto-cep
│── index.html
│── style.css
│── README.md
🌐 API Utilizada

O projeto utiliza a API pública:

🔗 https://viacep.com.br

Exemplo de requisição:

https://viacep.com.br/ws/01001000/json/
🔥 Integração com Firebase

O projeto utiliza Firebase para armazenar o último CEP consultado.

const FIREBASE_URL = "https://climatempo-gio-default-asia-southeast1.firebasedatakauanebase.app/cep/.json"
Funções principais:

salvarDados(cep) → Salva o CEP no banco

carregarDdos() → Recupera o CEP salvo

obterEndereco() → Consulta o endereço na API

⚠️ Observações Importantes

O CEP deve conter 8 dígitos numéricos.

Caso o CEP não exista, será exibida uma mensagem de erro.

É necessário ter um banco configurado no Firebase para o salvamento funcionar corretamente.

Há um pequeno erro no código:

campoCEP deve ser campoCep

carregarDdos pode ser corrigido para carregarDados

▶️ Como Executar

1.Baixe os arquivos do projeto.

2.Abra o arquivo index.html no navegador.

3.Digite um CEP válido.

4.Clique em Consultar.
