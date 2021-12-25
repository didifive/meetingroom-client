# Crie seu gerenciador de salas de reuniões com Java e Angular

## Digital Innovation One
### Bootcamp "Java Developer"

Projeto desenvolvido com instruções de [Kamila Santos] na trilha de estudo do Bootcamp "Java Developer" da [dio.me].

<p align="center">
	<img alt="Repository language count" src="https://img.shields.io/github/languages/count/didifive/lab-banco-digital-oo">
<a href="https://www.linkedin.com/in/falvojr/">
		<img alt="Made by Didi" src="https://img.shields.io/badge/made%20by-Didi-blue">
</a>	
<a href="https://github.com/didifive/lab-banco-digital-oo/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/didifive/lab-banco-digital-oo?color=blue">
</a>
<img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?color=blue">
</p>

<p align="center">
  <a href="https://angular.io/">
	  <img alt="Java" src="https://img.shields.io/static/v1?color=red&label=Dev&message=Angular&style=for-the-badge&logo=Angular">
	</a>
  <a href="https://www.typescriptlang.org/">
	  <img alt="Java" src="https://img.shields.io/static/v1?color=blue&label=Dev&message=TypeScript&style=for-the-badge&logo=Typescript">
	</a>
</p>

Link da base utilizada neste projeto: [Kamilahsantos/Client-Angular-Live-Coding-Dio].

Instalação do Angular CLI:
```bash
npm install -g @angular/cli
```

Abaixo seguem modificações feitas em relação ao projeto base:
* O projeto foi iniciado com `ng new` e componentes criados com `ng g c`;
* Como no backend foi criado novo atributo, neste projeto foi adicionado o atributo `link` no model `room.ts` e nos respectivos componentes `create-room`,`room-detais`, `room-list` e `update-room`;
* Foi adicionado o atributo `APIEndpoint` em environments para disponibilizar para a aplicação em `room.service.ts` os links para ambiente de desenvolvimento (local) e de produção (conectando com o projeto hospedado no [Heroku]).

---

O backend utilizado neste projeto está em [didifive/meetingroom-backend].

---

Links Interessantes:
* [NodeJS]
* [Angular CLI]
* [TypeScript]
* [Netlify]


[dio.me]: https://dio.me/
[Kamila Santos]: https://www.linkedin.com/in/kamila-santos-oliveira/
[Kamilahsantos/Client-Angular-Live-Coding-Dio]: https://github.com/Kamilahsantos/Client-Angular-Live-Coding-Dio
[didifive/meetingroom-backend]: https://github.com/didifive/meetingroom-backend
[NodeJS]: https://nodejs.org/
[Angular CLI]: https://angular.io/cli
[TypeScript]: https://www.typescriptlang.org/
[Netlify]:https://www.netlify.com/
[Heroku]: https://www.heroku.com/
