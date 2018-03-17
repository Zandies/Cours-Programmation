<style type="text/css">
*{
	/*display: flex;*/
	/*justify-content: center;*/
}
figure img{
	width: 500px;
	margin-top: 10px;
}
figure{
	display: flex;
	align-items: center;
	flex-direction: column;
}
#twitter{
	width: 170px;
}
#swift img{
	width: 100px;
	border-radius: 5px;
}
.questions, .informations{
	display: flex;
	justify-content: center;
	align-items: left;
}

.user_question, .user_information{
	display: flex;
	flex-direction: row;
	justify-content: center;
	align-items: center;
	border-radius: 2px;
	margin: -10px;
	width: 90%;
	color: #fff;
}

.user_question{
	background-color: #2980B988;
	border-left: 5px solid #2980b9;
}

.user_information{
	background-color: #EB323288;
	border-left: 5px solid #EB3232;
}

.user_question img{
	width: 40px;
}
.user_question p, .user_information p{
	color: white;
    padding: 15px 0px 0px 5px;
}
</style>

<img src="img/ARN_logoSite.png">

Cours d'initiation à la programmation
=====================================
@ilio Discepoli
Nicolas Gallis
Lucas Placentino

<div class="informations">
	<div class="user_information">
		<img src="img/exclamation.png" alt="alert"><p>Ce cours est destiné aux personnes souhaitant s'initier à la programmation informatique. Tout le code qui m'a servi à coder cette page est disponible sur GitHub</p>
	</div>
</div>

### Sommaire

* [C'est quoi la programmation ?](#prog)
	* [Pourquoi apprendre la programmation ?](#pk)
	* [Comment ca marche ?](#comment)
* [Quel langage choisir ?](#choix)
	* [Pour faire quoi ?](#pfk)
	* [Web ou machine ?](#)
	
<!-- --- Contenu --- -->

1. C'est quoi la programmation ? <a id="prog"></a>

	La programmation, c'est juste communiquer avec un ordinateur pour lui demander d'effectuer des actions pour nous. Bien que cela puisse sembler difficile d'un premier abord, la programmation est un univers accessible à n'importe qui, pourvu qu'on soit motivé. C'est comme parler dans une autre langue, on doit retenir des règles pour ensuite les appliquer et ainsi se faire comprendre par les personnes qui la parlent.
	Programmer, c'est créer des programmes. Il y'en a partout, aussi bien sur votre PC que sur votre smartphone en passant par les consoles et les appareils photos. 

	1. Pourquoi apprendre la programmation ? <a id="pk"></a>

		C'est une question légitime. De un, la programmation vous initie à une nouvelle façon de penser, quand vous aurez un petit bagage dans le monde du dévelopemment, vous verrez que ne pourrez vous empêcher d'imaginer la structure d'un programme que vous utiliser (aussi bien un site web qu'on jeu vidéo). De deux, ça vous apprend plein de chose sur l'informatique en général (comment fonctionne Internet, comment marche un PC, comprendre les messages d'erreurs barbares de Windows, <strike>pirater le réseau WiFi de l'école</strike>, ...)
		<figure>
			<img src="img/error.png">
			<figcaption>Une belle erreur comme on l'aime</figcaption>
		</figure>

	2. Comment ça marche ? <a id="comment"></a>
		Pour programmer, c'est tres simple. Il suffit de choisir un langage, de l'apprendre pour ensuite développer ce que l'on veut avec. Le code est ensuite interpreté par l'ordinateur pour pouvoir être executé. Il faut choisir un langage en fonction de vos envies (site web, jeu vidéo, logiciel,...)

2. Quel langage choisir ?<a id="choix"></a>
	
	Voici le premier vrai dilemme : Quel langage faut-il choisir ?
	Tout cela dépend de ce que vous voulez faire, je m'explique, si vous préferez coder des sites web, optez pour l'<strong style="color:#e74c3c;">HTML/CSS</strong>. Si vous préfèrez le monde des jeux vidéos<sup>(1)</sup>, le choix est beaucoup plus vaste: <strong style="color:#f1c40f;">C/C++, Python, Java, C#</strong>... Sinon, vous pouvez développez des applications IOS<sup>(2)</sup> avec le langage <strong style="color:#e67e22;">Swift</strong> ou l'<strong style="color:#e67e22;">Objective-C</strong>. Si vous êtes plutôt du genre à automatiser des tâches sur votre PC, il y'a le <strong style="color:#2ecc71;">Shell</strong>. 
	En bref, il existe des centaines de langages différents, pour tous les goûts, en cherchant vous trouverez sûrement celui qui vous parle :wink:
	<figure id="example_code">
		<img src="img/minecraft">
		<figcaption>(1) Minecraft, le jeu vidéo développé en Java</figcaption>
		<img src="img/twitter.png" id="twitter">
		<figcaption>(2) Twitter, une application dévelopée en Swift</figcaption>
	</figure>
	
	1. Je ne sais pas ce que j'aimerais faire, mais je veux vite voir le résultat ! <a href="#" id="pfk"></a>
		<div class="questions">
		<div class="user_question">
		<img src="img/question.png" alt="question"><p>Je ne sais pas ce que j'aimerais faire, mais je veux vite voir le résultat !</p>
		</div>
		</div>

		Alors là, je peux vous aider. 
		Si vous voulez commencer en douceur, apprennez le HTML/CSS qui permet de créer des sites web, c'est l'un des langage les plus faciles à apprendre, il est très simple à comprendre et c'est extrêmement visuel.
		<figure id="example_site">
			<img src="img/Website.png"/>
			<figcaption>Un site web développé en HTML/CSS</figcaption>
		</figure>
		Sinon, si vous êtes plus du genre jeux vidéo, il y a le Python qui permet d'en créer très simplement.
		<figure id="example_site">
			<img src="img/Pygame.png" alt title="Ouais... Vite fait quoi, j'avoue que pour développer un jeu pareil en Python, il faut y aller ! ^^" />
			<figcaption>Un jeu dévelloppé en python</figcaption>
		</figure>
		D'autre part, Apple à développé son propre langage qui permet de créer des applications pour appareils IOS assez simplement. Il s'agit de Swift. Au niveau de la "difficulté" à l'apprendre, il est presque identique au Python.
		<figure id="swift">
			<img src="img/swift.png" />
			<figcaption>Swift</figcaption>
		</figure>