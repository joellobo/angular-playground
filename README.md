# angular-playground
Angular Playground

$ lsb_release -a

No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 18.04.2 LTS
Release:	18.04
Codename:	bionic



curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
nvm install 8.9
npm install -g @angular/cli@6.0.7
ng new alurapic
cd alurapic/
npm install rxjs@6.0.0 --save
ng serve --open
