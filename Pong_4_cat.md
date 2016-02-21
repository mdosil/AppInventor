#Pong


Aquest tutorial us ensenyarà a construir un joc similar al famós joc arcade [Pong](http://www.ponggame.org/) creat per Atari el 1972. Vosaltres construireu la versió bàsica, tindreu una pilota que rebotarà a les 4 parets del mòbil i també hi haurà una plataforma mòbil a la part inferior sobre la qual haurà de botar la pilota sense que toqui a terra. La versió bàsica no tindrà ni marcador i el joc no tindrà un final. Però un cop l'hàgiu acabat podreu afegir-hi vosaltres mateixos aquests elements:

* Marcador amb la puntuació
* Acabar el joc quan la pilota toca el terra
* Afegir 3 vides a la pilota
* Afegir efectes de so


 Podeu trobar els videotutorials complets d'aquesta pràctica en anglès [aquí](http://www.appinventor.org/content/CourseInABox/drawAnimate/PongTutorial).





##Què aprendreu?

1. Instruccions condicionals **si entonces**, **si si no**
2. Instruccions condicionals encadenades



##PAS 1: Comencem

Connecteu-vos a l'App Inventor i baixeu-vos el  [*Pong_Basic template*](http://ai2.appinventor.mit.edu/?repo=templates.appinventor.mit.edu/trincoll/csp/unit5/templates/PongBasic/PongBasic.asc). Automàticament se us ha d'obrir la pestanya de "Mis Proyectos" i heu de veure un projecte anomenat **Pong Basic**. Canvieu-li el nom a **Pong_nomcognom**.


##PAS 2: Elements del joc Pong

Suposo que haureu vist que la plantilla del joc ja té varis elements creats: una etiqueta (LabelStart) dos botons (ButtonStart i ButtonReset), un element HorizontalArrangement1 que conté aquests 3 elements citats anteriorment i un llenç Canvas1. El Canvas1 té dos components, un component "Pelota" (Ball1) i un "ImagenSprite" (ImageSprite1). Aquests últims són components que es troben dins el calaix "Dibujo y animación" i ja en vau fer servir en el joc *Caça el Talp*.


![](img/pong_1_4.png)

Els components Pelota i ImagenSprite tenen moltes característiques semblants. Ambdós poden respondre a esdeveniments del tipus "tocar" i són sensitius a les col.lisions amb altres components Pelota i ImagenSprite així com a col.lisions amb les cantonades del llenç. Per tant, són ideals per a crear un joc com el Pong.

La única diferència és que un ImagenSprite pot tenir una imatge associada, com és ara un rectangle negre, que representa la plataforma.

##PAS 3: Dimensions del Llenç

Anem a veure ara algunes característiques importants del component "Lienzo" (llenç). Mireu la imatge següent:

![](img/pong_2_4.png)
