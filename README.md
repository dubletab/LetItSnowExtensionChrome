# LetItSnowExtensionChrome

Расширение Chrome для визуализации падающих снежинок на необходимых url'ах.

Чтобы снег отображался на требуемых url'ах в файле manifest.json прописываем требуемые сайты в 
            "matches": [
				"https://github.com/*",
				"https://vk.com/*"
			],
Если требуется на любом сайте прописываем следующее:
            "matches": [
				"https://*/*",
				"http://*/*"
			],


Для подключения расширения требуется включить режим разработчика в Расширениях Chrome (chrome://extensions/) и "Загрузить распакованное расширение". В открывшемся окне провалиться в папку с manifest.json.




https://hyperstown.github.io/puresnowjs/