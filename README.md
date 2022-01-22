# NGROK RDP by WarmyxPro
Windows Server 2019 Github with RDP Access (ngrok US) 
Ссылка на репозиторий: https://github.com/AbogusGames/ngrok_rdp

Бесплатный VPS сервер на WINDOWS SERVER с 2 ядрами -7gb ОЗУ бесплатно с помощью github:

*For Asia go to https://github.com/aloksharmakumar77/Windows2019RDP-AP*

+ Нажать FORK сверху в правом углу.
+ Заходим на https://dashboard.ngrok.com и берём токен авторизации
+ In Github go to Settings> Secrets> New repository secret
+ In Name: Вводим NGROK_AUTH_TOKEN
+ Значение: Заходим на https://dashboard.ngrok.com/auth/your-authtoken Копируем AuthTOKEN
+ Нажать Add secret
+ Go to Action> CI> Run workflow
+ Reload the page and press CI> build
+ Press the down arrow on Connect To Your RPD to get IP, User, Password.

*IF MY REPO GOT DELETED,ON YOUR GITHUB GO TO .github/workflows > RDP-US.yml AND EDIT NEW LINK TO YOUR REPO. ALL .BAT in Files FOLDER* 
