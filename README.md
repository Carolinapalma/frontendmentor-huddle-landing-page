# <h1 align="center">Frontend Mentor - Huddle Landing Page</h1>


## Indice

* [Visão geral](#visão-geral)
	* [Sobre](#sobre)
	* [Captura de tela](#captura-de-tela)
* [Processo](#processo)
	* [Contruído com](#contruído-com)
	* [Acesso a Página](#acesso-a-página)
	* [Autora](#autora)
---	

## <h2 align="center">Visão geral</h2>

### Sobre

- Huddle landing page witch single introductucory section solution - Frontend Mentor
This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

- View the optimal layout for the page depending on their device's screen size

- See hover states for all interactive elements on the page

---

## Captura de tela

<img src="src/images/Screenshot-desktop.gif" alt="gif tela inicial huddle page">

<br>

<img src="src/images/Screenshot-mobile.jpg" alt="screenshot versão mobile tela inicial huddle page">

---

### Construído com

* HTML semântica;
* FlexBox;
* CSS Grid

---

### O que aprendi
<br>

- Percebi que já possuo facilidade em incluir ícones customizaveis como fontes usando font-awesome:
```html
<div class="social">
	 <a href="">
			<i class="fab fa-facebook-square"></i>
```

- Tive maior familiaridade em usar CSS Grid:
```css
display: grid;
.body{
	grid-template-areas: 
	"header header"		
	"illustration about"
	"footer footer";
	grid-template-columns: repeat(2, 1fr);
	}
```

- Ainda tendo dificuldade, consegui realizar posicionamentos com FlexBox:
```css
.footer .social a{
	display: flex;
	justify-content: center;
	align-items: center;
}
```
<br>

>	Foi importante inicialmente analizar e estruturar o projeto antes de começar sua execução, com essa organização a construção da página foi feita de maneira mais rápida.

---

### Acesso a Página

- [GitHub Page]()

---

## <p align="center">Autora</p>

### Carolina Palma

* [LinkedIn](https://www.linkedin.com/in/carolina-palma-medeiros/)

* [GitHub](https://github.com/Carolinapalma)