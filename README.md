# Comparando UiPath e Automation Anywhere Aplicados ao Teste Automatizado da Interface Gr ́afica do Usuário

RPA significa "Automação de Processos Robóticos" (em inglês, Robotic Process Automation). É uma tecnologia que utiliza software ou "robôs" para automatizar tarefas repetitivas, baseadas em regras e que normalmente seriam realizadas por seres humanos. Essas tarefas podem envolver interações com sistemas de software, captura e manipulação de dados, preenchimento de formulários, processamento de transações, entre outras atividades.

Este experimento de trabalho de conclusão de curso visa analisar como os principais provedores de RPA se comparam ao criar um teste automatizado da interface gráfica do usuário. Os objetivos desse experimento são:

1. Identificar as dificuldades encontradas ao se implementar teste de
GUI nessas plataformas

2. Identificar as vantagens e desvantagens de cada plataforma
do ponto de vista do usuário ao implementar um teste de GUI

Nesse sentido, os participantes do experimento devem acessar as plataformas e realizar o download da versão gratuita dos softwares. Em seguida, devem assistir um tutorial em que é explicado como as plataformas funcionam e implementar um caso de teste.

Os requisitos para a realização desse experimento são: ter uma máquina com o sistema operacional Windows e utilizar o navegador Google Chrome.

# UiPath

### Login

Primeiramente, acesse a página de login nesse [Link](https://account.uipath.com/login?state=hKFo2SB5YkFvQS10eVFaM1BmbXFKN0NYclpjaFhoU2pjaDJKRqFupWxvZ2luo3RpZNkgcDd0cTB6a0ZJNHBJSTF1bVViWlYzckVwcktzeXlXTGKjY2lk2SAyeXQ5SGRGNDVPMDA2SDlxZFBjUDlhczVjZEdibkNXcw&client=2yt9HdF45O006H9qdPcP9as5cdGbnCWs&protocol=oauth2&audience=https%3A%2F%2Fuipath.eu.auth0.com%2Fapi%2Fv2%2F&scope=openid%20profile%20email%20read%3Acurrent_user%20update%3Acurrent_user_metadata&redirect_uri=https%3A%2F%2Fcloud.uipath.com%2Fportal_%2FauthCallback&type=login&ecommerceRedirect=false&redirectPath=&marketplaceRedirectUri=&retryUrl=%2Fportal_%2Fenterprisesso&product_name=UiPath%20Automation%20Cloud&company_code=B2B_CP&platform_name=UiPath%20Platform&enable_marketing_fields=true&cloudrpa_signup_subdomain=%2Fportal_&register_endpoint=%2Fregister&use_local_registration=false&response_type=code&response_mode=query&nonce=RjhvekdlZ01tOHdRbk5yTW5kaGtFVkl1RlltY2tjd0lmUGVwSnBURmhrVg%3D%3D&code_challenge=9XfM3Cax5FreVUE7qfdYW7au5Iyh5iP-NwjErSsHJuE&code_challenge_method=S256&auth0Client=eyJuYW1lIjoiYXV0aDAtcmVhY3QiLCJ2ZXJzaW9uIjoiMS4yLjAifQ%3D%3D) e acesse a plataforma com as credenciais disponibilizadas.


### Download

![image](/images/download_uipath.png)

Na página principal do UiPath, clique no botão "Download" localizado na direita.


Execute o arquivo "UiPathStudioCommunity.msi" que foi baixado anteriormente, selecione a opção de instalação Rápida e aguarde, durante a instalação do UiPath será requerido a instalação de uma extensão para o Chrome, em que será necessário fechar o navegador.

![image](/images/uipath_studio_config.png)

Após a instalação, execute o UiPath Studio, faça login, selecione o perfil UiPath Studio, feche a janela de Boas Vindas. Caso queira, é possível mudar o tema e é recomendável utilizar o software em inglês que pode ser mudado no menu de configurações,

### UiPath Academy

Acesse a página do UiPath Academy nesse [Link](https://academy.uipath.com/) e clique em Login/Sign up no canto superior direito. Faça login com a suas credenciais do UiPath.


![image](/images/ui_path_resume_course.png)
Em seguida, acesse o curso "Application Testing with UiPath Test Suite" nesse [Link](https://academy.uipath.com/courses/application-testing-with-uipath-test-suite) e clique em "Resume Course"

![image](/images/testing_ui.png)
Para o presente experimento, apenas as aulas ("Creating and publishing an object repository for application testing" e "Using an object repository to create test cases") do módulo "Testing the User Interface" são relevante

### Crie um caso de teste

Agora prossiga para a seção "Experimento: Criando um caso de teste do Clockify" deste tutorial e crie um caso de teste como específicado


## Automation Anywhere

### Login

Acesse a pagina de login do Automation Anywhere nesse [Link](https://community.cloud.automationanywhere.digital/). Realize o Login com as credencias disponibilizadas


### Configuração

![image](/images/aa_connect.png)

Conecte o seu dispositivo selecionando a opção no canto inferior esquerdo e clique em "Connect Local Device", em seguida "Connect to my computer"

![image](/images/aa_connect.png)

Será instalado o Bot Agent(AARI) e uma extensão ao Google Chrome. 

![image](/images/aa_device.png)

Após isso, certifique-se que o seu dispositivo está conectado.


### Automation Anywhere University

![image](/images/aau_login.png)

Acesse a página de login do Automation Anywhere University nesse [Link](https://apeople.automationanywhere.com/sso/s/login/?startURL=%2Fsso%2Fidp%2Flogin%3Fapp%3D0sp6F000000XZKC%26RelayState%3Dhttps%253A%252F%252Funiversity.automationanywhere.com%252Fsimplesaml%252Fmodule.php%252Fcore%252Fauthenticate.php%253Fas%253Ddefault-sp%2526cid%253D%2526lp%253D%2526co%253D%2526checkout%253D%2526dfor%253D%2526lang%253D%2526ilt%253D%2526ilts%253D%2526mid%253D%2526rurl%253D%2526lsubs%253D%2526st%253D%26binding%3DHttpPost%26inresponseto%3D_e359eaa5e9b973358cc6fd632e771d24fbb25dd870). Informe o seu email e senha e realize o login.



![image](/images/aaU_course_enroll.png)

Após criar a sua senha, faça login no Automation Anywhere University e começe o curso ["Building your first Automation Bot"](https://upskill.automationanywhere.com/courses/building-your-first-automation-bot)

![image](/images/aa_lectures.png)

Acesse o módulo "Building Your First Automation Bot - Creating and Running Your Bot", clique no botão "Open content in New Window" para acessar o conteúdo do curso. Assista as duas primeiras aulas "Creating the IT Bricks Bot" e "Extracting Data from a Web Portal into a CSV File".

Por fim, volte na seção "Experimento: Criando um caso de teste do Clockify" deste texto, e crie novamente o caso de teste, dessa vez utilizando o Automation Anywhere.


# Experimento: Criando um caso de teste do Clockify

![image](/images/clockify_login.png)

Após assistir o tutorial, chegou a sua vez de criar um caso de teste. Nesse caso de teste, você deve realizar o login no software [Clockify](https://app.clockify.me/en/login) com email e senha.

![image](/images/logout_clockify.png)

Em seguida, deve clicar no icone de perfil no canto superior direito, coletar o nome do usuário (Xiwirij646) para ser validado e realizar o logout.


# Questionário e Entrevista

Por fim, após criar o caso de teste no UiPath e no Automation Anywhere, responda o questionário nesse [Link](https://forms.gle/DXp8izxBjpirjFxH7) e participe da entrevista.