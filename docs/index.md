---
hide:
    - navigation
---

# Bienvenue sur Loop

Ce site se nomme "LoopDocs", traduit du [site web original](https://loopkit.github.io/loopdocs/) par une équipe de bénévoles. Ici, vous pouvez tout apprendre sur Loop. Avant de commencer, veuillez lire **toutes les pages** avec soin et prêtez toute votre attention dessus, pour non seulement construire Loop avec succès, mais surtout pour l'utiliser en toute sécurité.

Il se peut que vous vous sentez envahi.e de nouvelles informations ou que vous soyez un peu stressé.e à l'idée de vous lancer dans la création de votre propre application iPhone, mais ne le soyez pas. Ce site contient des instructions, étape par étape, avec des captures d'écran et des flèches utiles pour chaque étape. Nous n'attendons pas des utilisateurs qu'ils aient des connaissances techniques ou informatiques préalables. Les mots peuvent être très étranges ou même parfois en anglais pour certains concepts, mais de nombreuses captures d'écran vous permettront d'y arriver même si vous ne connaissez pas la signification de certains mots. Ce site, ainsi que l'original, est mis à jour régulièrement afin de suivre l'évolution de Loop.

Pour vous aider, des boutons de navigation se trouvent au bas de chaque page des LoopDocs. Ainsi, lorsque vous avez terminé une étape ou un sujet, cliquez sur le lien vers la page suivante pour continuer. Il y a également un outil de recherche dans le coin supérieur droit pour les cas où vous ne savez pas où trouver une information.

Enfin, nous vous recommandons vivement de lire les pages FAQ, disponible sous peu en français mais [qui se trouve ici en anglais sur le site d'origine](https://loopkit.github.io/loopdocs/faqs/docs-faqs/), plusieurs fois au cours de la construction et de l'utilisation de votre application Loop. Comment changer votre émetteur et capteur Dexcom, comment changer les pods, comment mettre en place un nouvel iPhone, comment construire Loop avec un ordinateur Windows, combien Loop coûte, etc... tout est dans la foire aux questions.

## Introduction

* Loop est une application mobile que vous créez vous-même et que vous chargez sur un iPhone ou un iPod.
* Loop prédit l'évolution de votre glycémie en fonction de la consommation des glucides, de l'insuline active dans votre coprs, des données du CGM et de vos paramètres thérapeutiques personnles (par exemple, le ratio de glucides, débits de base, etc.)
* Sur la base de cette courbe de prédiction, Loop effectue automatiquement (en mode boucle fermée) ou propose (en mode boucle ouverte) des modifications de l'administration d'insuline pour ramener votre glycémie dans la plage cible spécifiée.
* Loop nécessite [un CGM compatible](construire/etape3.md) et [une pompe à insuline compatible](construire/etape4.md).
* Pour les personnes utilisant une pompe Medtronic ou des Omnipod Eros compatibles, vous aurez également besoin d'[un petit dispositif](construire/etape5.md) pour que l'iPhone et la pompe puissent communiquer entre-eux. A l'origine, il n'existait qu'une seule option pour ce dispositif, appelé RileyLink. De nouvelles options sont désormais disponibles, en plus du RileyLink de base, avec des avantages et des inconvénients différents pour chacune. Les utilisateurs des Omnipod DASH n'ont pas besoin de ce dispositif, car les pods sont déjà équipés du Bluetooth.

![Loop main display on phone](img/phone_updated_loop.svg){width="300"}
![Loop watch screen on watch](img/watch_updated_loop.svg){width="300"}

## Histoire du développement

Loop est un projet open-source et partagé. L'ensemble du projet a été, et continue d'être, réalisé par des bénévoles. Du code au site web, vous obtenez tout cela parce que des dizaines de bénévoles ont donné de leur temps. Alors, s'il vous plaît, accordez-nous votre temps en retour en lisant attentivement ce site web avant de vous embarquer dans votre voyage Loop.

En plus de ce site web, voici des liens vers d'autres ressources que vous pourrez explorer :

* Les débuts du développement de Loop : [Histoire de Loop et LoopKit (en)](https://medium.com/@loudnate/the-history-of-loop-and-loopkit-59b3caf13805), écrit par le développeur de Loop, Nate Racklyeft.

* Les premiers jours et de nombreux progrès réalisés par la communauté des diabétiques We Are Not Waiting : [The Artificial Pancreas Book (en)](https://www.artificialpancreasbook.com/), écrit par Dana Lewis, et son site web [DIYPS (en)](https://diyps.org).

* Comment les Omnipod Eros ont été modifiés pour fonctionner avec Loop : [Insulin Pumps, Decapped Chips and Software Defined Radios (en)](https://medium.com/@ps2), écrit par le développeur de Loop Pete Schwamb and [Deep Dip Teardown of Tubeless Insulin Pump (en)](https://arxiv.org/ftp/arxiv/papers/1709/1709.06026.pdf) par Sergei Skorobogatov.


!!! warning "Attention"
    Veuillez comprendre que ce projet :

    - Est hautement expérimental
    - N'est pas approuvé pour l'insulinothérapie

    **_Vous assumez l'entière responsabilité de la construction et du fonctionnement de ce système et vous le faites à vos propres risques._**

## L'outil de recherche

Il n'est pas rare d'avoir une question sur Loop. Mais il est exceptionnellement rare que la question n'ait pas déjà trouvé de réponse dans LoopDocs, que ce soit sur ce site ou sur l'original. Nous vous invitons donc à ajouter ce site et l'original à vos favoris et à **cherchez des réponses** en utilisant les menus de navigation ou l'outil de recherche qui se trouve dans le coin supérieur droit de ce site.

Recherchez des sujets en cliquant sur l'outil de recherche, ou en tapant la lettre "s" sur votre clavier. Lorsque vous commencez à taper, des suggestions et des liens vers des pages s'afficheront.

<br/><br/>![example of using search](img/new-look-search-example.png){width="600"}<br/>`


## Se tenir à jour ou trouver de l'aide

Comme il s'agit d'un projet utilisé et développé par des volontaires collaborant à distance, la plupart du support et des conversations se font via des plateformes en ligne. Il y a [un nombre d'options](constuire/etape12.md) pour que vous puissiez participer à ces conversations ou demander de l'aide. Les liens vers les principales plateformes sont indiqués ci-dessous.

* Le moyen le plus rapide d'obtenir de l'aide, avec le plus de mentors, est [le groupe Facebook de Looped (en)](https://www.facebook.com/groups/TheLoopedGroup). Ce groupe est le groupe Facebook d'origine pour les systèmes de boucle fait maison (DIY). Il y a beaucoup de membres actifs qui ont l'habitude d'aider les gens.

* Nous avons également l'équivalent du groupe Looped en français sur [le groupe Facebook Looped France](https://www.facebook.com/groups/loopedfrance).

* Il existe un autre groupe Facebook, Loop and Learn, qui propose de nombreuses informations sur le système Loop, une série de conférences en anglais sur le diabète de type 1 couvrant de nombreux sujets d'intérêt général, ainsi que des discussions spécifiques au système Loop, des alertes en cas de mise à jour d'iOS et de Xcode, des conseils rapides et des articles rédigés par des mentors faisant part de leur expérience du système Loop.
    * [Groupe Facebook de Loop and Learn (en)](https://www.facebook.com/groups/LOOPandLEARN)
    * [Site web de Loop and Learn (en)](https://www.loopandlearn.org)
 
 * Le site web [LoopTips (en)](https://kdisimone.github.io/looptips/) fournit des informations qui ne sont pas liées à la construction et constitue plutôt une ressource du type "maintenant que j'utilise une boucle fermée DIY..." pour savoir comment imprimer des rapports pour votre diabétologue, trouver des données de Loop, gérer les changements de paramètres thérapeutiques, etc.
 
 * Beaucoup de "Loopers" utilisent [Nightscout](nightscout/apercu.md). Vous trouverez de l'aide sur Nightscout sur les groupes Facebook [CGM in the Cloud (en)](https://www.facebook.com/groups/CGMinthecloud) et [Nightscout France](https://www.facebook.com/groups/829984313773612). 
 
 * Pour ceux qui ne sont pas intéressés par Facebook ou qui s'intéressent à l'avenir de Loop, rejoignez [Loop Zulipchat (en)](https://loop.zulipchat.com) et assurez-vous de vous abonner à tous les flux, sinon vous raterez des conversations intéressantes.
 
 * Loop a également un compte Instagram [@diy.loop](https://www.instagram.com/diy.loop/) où les mises à jour sont également partagées.

#### Cherchez, puis demandez

!!! danger "Comment demander de l'aide"

    Si vous avez des difficultés à créer ou à utiliser votre application Loop, il existe quelques étapes importantes pour vous aider à obtenir des réponses à vos questions, tout en respectant le temps de nos bénévoles.
    
    1. Cherchez toujours dans **les deux** [LoopDocs](#search-tool) et dans le groupe Looped. Vous ne savez pas comment faire une recherche ou utiliser le groupe Looped ? [Voici une vidéo](https://www.youtube.com/watch?v=_vSN6C-Uo04) pour vous aider.
    
    2. Cliquez sur la section Annonces du groupe Looped ; près d'un tiers des messages demandant de l'aide ces jours-ci trouvent déjà une réponse dans les annonces épinglées.
        Forcer nos bénévoles à répondre de manière répétée à la même question est un moyen sûr d'épuiser ces volontaires.
        
    3. Ne posez pas une question en double dans plusieurs groupes (les mentors surveillent de nombreux groupes, vos administratrices du groupe Looped France sont également modérateurs dans Loop and Learn, Nightscout France...). Ne postez dans un autre groupe que si vous n'avez pas eu de réponse pendant plusieurs heures.
    
    4. Si une recherche dans LoopDocs, une recherche sur Facebook et une vérification des annonces des groupes Looped et Looped France n'ont pas permis de répondre à votre question, postez une demande d'aide. Révisez les [conseils sur la façon de demander de l'aide](construire/etape12.md) afin que nos bénévoles obtiennent toutes les informations dont ils auront besoin pour vous aider, sans avoir à poser 40 questions au préalable.
    
    5. Laissez votre question affichée même après avoir obtenu une réponse, mais modifiez le message original pour ajouter le mot **RÉSOLU** au début du message original.
        * Cela aide les autres Loopers qui ont la même question.
        * Cela permet aux mentors de savoir qu'ils n'ont pas besoin de répondre pour vous aider.

## Améliorations des LoopDocs

Veuillez soumettre vous suggestions de mise à jour et d'amélioration de cette documentation. Il y a de nombreuses pages de contenu et nous invitons les réviseurs à nous aider à trouver les coquilles et les informations / liens périmés. Si vous remarquez une coquille, un mauvais choix de mots ou une explication qui pourrait être améliorée ou clarifiée, il existe quelques options. Les deux premières option utilisent Github, un site web où le code open-source est souvent partagé.

1. Vous pouvez faire un pull request (meilleure option s'il s'agit d'une simple coquille ou d'une mise à jour de la tournure d'une phrase)

2. Vous pouvez ouvrir un Issue (meilleure option si une réécriture majeure est nécessaire ou si vous pensez qu'une conversation serait utile), ou

3. Vous pouvez poster sur le groupe Looped France


### Pull Requests et Issues

Si vous décidez de faire une Pull Request (PR) via Github ou de créer un Issue, regardez d'abord si le problème existe uniquement sur les LoopDocs français, ou s'il est également présent sur les LoopDocs d'origine. En bas de chaque page, un lien est présent pour vous diriger vers la page d'origine des LoopDocs.

Si le problème est présent uniquement sur les LoopDocs français, regardez ensuite si quelqu'un a déjà ouvert une [PR]() ou un [Issue]() sur le sujet au Github des docs français afin de ne pas créer un doublon.

Si le problème est présent également sur les LoopDocs d'origine, regardez ensuite si quelqu'un a déjà ouvert une [PR](https://github.com/LoopKit/loopdocs/pulls) ou [Issue](https://github.com/LoopKit/loopdocs/issues) sur le Github des docs anglais sur le sujet afin de ne pas créer un doublon.

Si une PR ou une question sur le sujet est ouverte, n'hésitez pas à ajouter vos commentaires, mais ne créez pas de doublon.

* Si une PR n'existe pas, regardez [cette vidéo, en anglais, sur les Loopdocs Pull Request](https://youtu.be/6qSppvgGxpg) pour savoir comment en créer une (la vidéo dure moins de 5 minutes).

* Si votre problème est nouveau, veuillez l'ajouter en cliquant sur le bouton `New Issue`.
    * Donnez un titre descriptif à la publication
    * Indiquez la ou les pages à mettre à jour, ainsi qu'une brève description du ou des problèmes.

### Facebook ou Zulipchat

Conseil utiles pour faire des commentaires sur LoopDocs via Facebook et / ou Zulipchat :

* Dans [le groupe Looped](https://www.facebook.com/groups/TheLoopedGroup) ou [Looped France](https://www.facebook.com/groups/loopedfrance) - assurez-vous que votre message indique clairement que votre commentaire concerne LoopDocs en particulier.

* Dans le Zulipchat de Loop, veuillez utiliser le canal [documentation stream, Loopdocs Issue](https://loop.zulipchat.com/#narrow/stream/270362-documentation/topic/Loopdocs.20Issue)


## Repositories et Code

Si vous êtes un développeur à la recherche de liens directs vers le code et la documentation de Github :

* [Loop](https://github.com/LoopKit/Loop) 
* [LoopDocs (version originale)](https://github.com/LoopKit/Loopdocs)
* [LoopDocs (version française)]()

Pour plus d'informations sur la façon de contribuer au code du projet, veuillez consulter :

 * [Comment contribuer à l'Open Source (en)](https://opensource.guide/how-to-contribute/)
 
 * Révisez la [LICENSE de Loop](https://github.com/LoopKit/Loop/blob/master/LICENSE.md)
 
 * Révisez le [CODE_OF_CONDUCT](https://github.com/LoopKit/Loop/blob/master/CODE_OF_CONDUCT.md)

Si vous souhaitez contribuer à l'amélioration du code, rejoingez le [Zulipchat de Loop](https://loop.zulipchat.com) et assurez-vous de vous abonner à tous les canaux. Rencontrez les développeurs et les testeurs qui ont créé cette application, et découvrez les prochaines évolutions.
