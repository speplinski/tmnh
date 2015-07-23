# T-Mobile Nowe Horyzonty #

Strona T-Mobile Nowe Horyzonty na 15. Międzynarodowy Festiwal Filmowy, Wrocław, 23 lipca - 2 sierpnia 2015.

## Tagi Open Graph ##

Wszystkie pliki HTML zawierają [tagi og:url i og:image](https://developers.facebook.com/docs/sharing/best-practices), które wskazują bezpośredni link do finalnego adresu strony.
Jeśli ten adres uległby zmianie, konieczna będzie modyfikacja.

```
<meta property="og:url" content="http://www.t-mobile-trendy.pl/t-mobile-nowe-horyzonty/2015/"/>
<meta property="og:image" content="http://www.t-mobile-trendy.pl/t-mobile-nowe-horyzonty/2015/img/fb.png"/>
````
## Kod QR do pobrania aplikacji ##

Na podstronie [aplikacja.html](aplikacja.html) w wersji desktop dostępny jest kod QR, który pozwala po zeskanowaniu go telefonem automatycznie przełączyć się do wybranego sklepu (np. App Store).
Kod ten ma zaszyty skrócony adres URL do pliku [pobierz-aplikacje.html](pobierz-aplikacje.html).
Jeśli adres docelowy były inny niż [http://www.t-mobile-trendy.pl/t-mobile-nowe-horyzonty/2015/pobierz-aplikacje.html](http://goo.gl/dfG5KB), wówczas należy podmienić [kod QR](img/kod.png).
Można w tym celu posłużyć się [generatorem kodów QR](http://qrcode.kaywa.com).
Ważne, aby wygenerowany kod miał rozmiar 216x216 px.

## Aktualności ##

Aktualności powinny być pobierane dynamicznie. W pliku [aktualnosci.html](aktualnosci.html) znajduje się struktura.
Wiadomości poninny układać się naprzemiennie. Definiują to klasy *col-md-push-5* oraz *col-md-pull-7* .
Dodatkowo jeśli w nagłówku *h2* pojawi się zwrot *T-Mobile Nowe Horyzonty* lub *T-Mobile* powinien dostać klasę *tmcolor*.

````
<div class="row featurette">
	<div class="col-md-7">
		<h2 class="featurette-heading fbold">Czekamy na Wasze zdjęcie z <span class="tmcolor">T-Mobile Nowe Horyzonty</span></h2>
		<p class="lead fplain">Organizatorzy festiwalu chcą stworzyć galerię zdjęć, dokumentującą 15 lat trwania imprezy. Macie fotki, które warto pokazać innym?</p>
	</div>
	<div class="col-md-5">
		<a href="//www.t-mobile-trendy.pl/artykul,9006,czekamy_na_wasze_zdjecie_z_t-mobile_nowe_horyzonty,film,320.html" target="_blank">
			<img class="featurette-image img-responsive center-block" src="//www.t-mobile-trendy.pl/files/article/37f9162863ab2c1a85c9b05ba4e89ca6/tnh_amichalak.png" alt="">
		</a>
	</div>
</div>

<hr class="featurette-divider">

<div class="row featurette">
	<div class="col-md-7 col-md-push-5">
		<h2 class="featurette-heading fbold"><span class="tmcolor">T-Mobile</span> zaprasza do Placu Zabaw nad Wisłą</h2>
		<p class="lead fplain">Na odwiedzających czekają seanse filmowe „T-Mobile Nowe Horyzonty na Placu Zabaw” oraz strefa SPEED ST4GE.</p>
	</div>
	<div class="col-md-5 col-md-pull-7">
		<a href="//www.t-mobile-trendy.pl/artykul,8994,t-mobile_zaprasza_do_placu_zabaw_nad_wisla,technewsy,20.html" target="_blank">
			<img class="featurette-image img-responsive center-block" src="//www.t-mobile-trendy.pl/files/article/8d9f21a3d74932040890d738f51812c0/wisla.jpg" alt="">
		</a>
	</div>
</div>
````

## Społeczność ##

Społeczność powinna być pobierana dynamicznie. Jednorozowo nie powinno być wyświetlanych więcej niż 100 elementów.
W pliku [spolecznosc.html](spolecznosc.html) znajduje się struktura.
Jeśli w treści występuje hashtag (wyzaz z # na początku), powinien on dostać link który wygląda następująco *https://twitter.com/hashtag/NAZWA_HASHTAGU_BEZ_ZNAKU_HASH*, np.

````
<a class="fbold" href="https://twitter.com/hashtag/tnh2015" target="_blank">#tnh2015</a>
````

Podobnie wszystkie adresy URL występujące w treści powinny kierować do właściwych stron.
Link do całości artukułu znajduje się po nazwie autora w tagu *<p class="user fplain">* .

````
<div class="pin">
	<p class="fplain">
		to będzie kilka dni mnóstwa dobrych filmów. jestem cinephile. <a class="fbold" href="https://twitter.com/hashtag/tnh2015" target="_blank">#tnh2015</a> <a class="fbold" href="https://twitter.com/hashtag/wroclaw" target="_blank">#wroclaw<a/> <a class="fbold" href="https://twitter.com/hashtag/foto" target="_blank">#foto</a> <a class="fbold" href="https://twitter.com/hashtag/igerswroclaw" target="_blank">#igerswroclaw</a> <a class="fbold" href="https://t.co/2XWHc7BPSb" target="_blank">https://t.co/2XWHc7BPSb</a>
	</p>
	<p class="user fplain">
		tfurca <a href="http://twitter.com/tfurca/statuses/623877357015822336" target="_blank"><i style="float:right;padding-top:5px" class="fa fa-external-link"></i></a>
	</p>
</div>
````