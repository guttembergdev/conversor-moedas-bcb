💱 Conversor de Moedas - BCB

Conversor de moedas desenvolvido em PHP que consome a API oficial do Banco Central do Brasil (ou AwesomeAPI) para obter cotações atualizadas. Permite converter valores entre Real (BRL), Dólar (USD) e Euro (EUR).

---

🚀 Tecnologias utilizadas

- PHP
- HTML5
- CSS3
- JavaScript
- API pública de câmbio (AwesomeAPI ou BCB)

---

📦 Como rodar localmente

1. Instale o [XAMPP](https://www.apachefriends.org/pt_br/index.html)
2. Clone este repositório ou baixe os arquivos
3. Coloque os arquivos na pasta `htdocs` do XAMPP
4. Inicie o Apache pelo painel do XAMPP
5. Acesse no navegador:  
   `http://localhost/conversor-moedas-bcb`

---

🔗 Exemplo de requisição

```php
$url = "https://economia.awesomeapi.com.br/json/last/USD-BRL,EUR-BRL";
$data = json_decode(file_get_contents($url), true);
