# PayPal Transparent Checkout for OpenCart 2 and 3
! [] (https://raw.githubusercontent.com/wiki/paypal/PayPal-PHP-SDK/images/homepage.jpg)

The experience of a Transparent Checkout processed with the security of PayPal. Your customer makes the payment directly on your website, without redirection and without the need to open a PayPal account, using credit card data, which can be saved to speed up the payment process. payment on future purchases.


## Requirements

For the correct functioning of the solutions, it is necessary to check if your store and server support some features:
1. For transparent checkout (PayPal Plus), your store needs to support the CPF (Account type) and Number (Address type) fields, so before activating the solution, ensure that your store is properly configured to support these fields;
2. The server must support PHP 7.3 or higher;
3. The server must support TLS 1.2 or higher and HTTPS 1.1 [(Official Reference)] (https://www.paypal.com/sg/webapps/mpp/tls-http-upgrade).

## Transparent Checkout (PayPal Plus)

The Transparent Checkout is only available for PayPal accounts registered with CNPJ (Corporate Account), if your account is for an individual, you must open a PayPal account for a legal person through this [link] (https://www.paypal.com / bizsignup /).

The solution requires commercial approval, contact 0800 721 6959 and request now.

*** The Transparent Checkout will only work if it has been approved by PayPal. **

## Compatibility

This module is compatible with OpenCart versions 2.0.1.1 to 3.0.3.6.

## Installation

1. Download the module compatible with your version of OpenCart, then access your store administration;
2. Go to the menu ** Extensions → Installer **, click on the "** Upload **" button, locate the file you downloaded, and wait for the automatic installation to complete;
3. Go to the menu ** Extensions → Modifications ** and click on the "** Update **" button;
4. In OpenCart 3, go to the menu ** Control panel **, on the right side of the screen under the button "** Exit **", click on the button in blue with the design of a white gear on it, in modal click on the two orange buttons inside the "** Action **" column to update the theme cache;
5. Go to the menu ** Extensions → Payments ** (in versions 2.3 or higher go to the menu ** Extensions → Extensions ** and filter for ** Payments **), find the extension "** PayPal Plus **", click the "** Install **" button, then the "** Edit **" button, fill in the fields and click the "** Save **" button.

## Settings
### - API Credentials
To configure PayPal solutions, you must generate REST-type API credentials, in this case Client ID and Secret ID.

To obtain them follow this step-by-step:
                
1. Log in with your PayPal account at https://developer.paypal.com and click on the link at the top "** Dashboard **"; 
2. Clique em "**My Apps & Credentials**";
3. Abaixo de "**Rest API apps**" clique em "**Create App**";
4. Em seguida, insira o termo "**ppplus**" no campo "**App Name**" e clique em "**Create App**";
5. No canto superior direito da tela, clique em "**Live**";
6. Você deve copiar os códigos que aparecerem em "**Client ID**" e em "**Secret**" (para visualizar o "Secret" será necessário clicar em "**Show**") e colar estes códigos na página de configuração da solução que irá utilizar. 

### - Solução

Para o Checkout Transparente funcionar, sua loja precisará ter cadastrado os campos CPF (tipo Conta) e Número (tipo Endereço).

Para cadastrá-los siga este passo-a-passo dentro do painel administrativo do seu OpenCart:

Vá ao menu **Clientes→Personalizar cadastro**, e clique no botão **Novo**.

Para cadastrar o **CPF**, preencha o formulário com as informações abaixo:

| Campo | Valor |
| -------- | ----- |
| Nome do campo | CPF |
| Localização | Conta |
| Tipo de campo | Texto em uma linha |
| Tipo de cliente | Marque os tipos de clientes que verão o campo durante o cadastro |
| Tipos obrigatórios | Marque os tipos de clientes que terão o campo como preenchimento obrigatório |
| Situação | Habilitado |

Após preencher o formulário, clique no botão **Salvar**.

Para cadastrar o **Número**, clique novamente no botão **Novo** e preencha o formulário com as informações abaixo:

| Campo | Valor |
| -------- | ----- |
| Nome do campo | Número |
| Localização | Endereço |
| Tipo de campo | Texto em uma linha |
| Tipo de cliente | Marque os tipos de clientes que verão o durante o cadastro |
| Tipos obrigatórios | Marque os tipos de clientes que terão o campo como preenchimento obrigatório |
| Situação | Habilitado |

Após preencher o formulário, clique no botão **Salvar**.

## Dúvidas/Suporte

Caso a sua dúvida não tenha sido respondida aqui, entre em contato com o PayPal pelo número 0800 047 4482.

E caso necessite de algum suporte técnico e/ou acredita ter encontrado algum problema com este módulo acesse o nosso [portal de suporte técnico](https://www.paypal-support.com/s/?language=pt_BR) e abra um ticket detalhando o seu problema na seção "Fale Conosco".

## Changelog

Para visulizar as últimas atualizações acesse o [**CHANGELOG.md**](CHANGELOG.md).
