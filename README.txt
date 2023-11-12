Drugi projekt iz Web2

###########################################################################

Adresa git repozitorija s web-aplikacijom  https://github.com/jelenakulisic/web

Adresa web-aplikacije https://sigurnost-web-p3xh.onrender.com

Popis implementiranih ranjivosti:

1. Cross-site scripting (XSS)
2. Nesigurna pohrana osjetljivih podataka (Sensitive Data Exposure)

Napomene:
Obje ranjivosti su implementirane. 

Upute kako lokalno pokrenuti i isprobati aplikaciju:
- otvoriti adresu web aplikacije
- za xss kliknuti checkbox ovisno o tome zelimo li ukljuciti ranjivost, nakon toga upisati komentar u input,
npr. <script>alert("Hi")</script>, kada je ranjivost ukljucena pojavit ce se alert prozor, a kada nije ukljucena nece
- za nesigurnu pohranu osjetljivih podataka upisati neku tajnu poruku u input, kada je ranjivost ukljucena tajna poruka
prikazivat ce se normalno, a kada nije ukljucena ranjivost prikazivat ce se hash tajne poruke

