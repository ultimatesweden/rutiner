# Hemsida

Hemsidan (http://ultimatesweden.se) används för att sprida information försäljning och även att ta in anmälningar och betalningar till olika event.

I tillägg till hemsidan som är synlig för medlemmarna finns en testmiljö och en utvecklingsmiljö. Dessa kan användas om man vill testa
ny funktionalitet eller bara lära sig lite om Wordpress och WpForms. Maila hemsida@ultimatesweden.se om du har frågor kring detta.


## Formulär - WpForms

WpForms gör det enkelt att sätta upp formulär som kan användas för att ta in anmälningar och även betalningar.


### Se formulär/anmälningar/betalningar


![Meny](./media/WpForms/Meny.png "Meny")

![Entries](./media/WpForms/Entries.png "Entries")

![Export_CSV](./media/WpForms/Export_CSV.png "Export_CSV")


### Skapa ny sida med formulär

Ett enkelt sätt att skapa en sida med ett formulär i är att kopiera en existerande sida.

1. Börja med att kolla vilket ID det formulär som ska användas har (vi förutsätter att formuläret redan finns). Välj menyvalet 'All Forms'

![Meny wpforms](./media/WpForms/meny-wpforms.png "Meny wpfroms")

2. Kontrollera vilket ID som det formulär du vill använda har i listan med formulär, t.ex. ```[wpforms id="XXXX"]```

![Se wpforms id](./media/WpForms/se-wpforms-id.png "Se wpforms id")

3. Välj sedan listan med alla sidor

![Meny sidor](./media/WpForms/meny-sidor.png "Meny sidor")

4. Duplicera en sidan som liknar den sida du vill skapa

![Duplicera sida](./media/WpForms/duplicera-sida.png "Duplicera sida")

5. Välj Redigera för denna sida

![Meny Redigera sida](./media/WpForms/redigera-sida.png "Meny Redigera sida")

6. Ändra ID i sektionen ```[wpforms id="XXXX" ...]```. Ändra övrig text.

![Uppdatera sida](./media/WpForms/sida.png "Uppdatera sida")

7. Publicera sidan

![Publicera sidna](./media/WpForms/publicera.png "Publicera sida")

8. Uppdatera menyerna

![Menyer](./media/WpForms/menyer.png "Menyer")

9. Välj sidan du skapade och sedan 'Lägg till i meny'

![Lägg till meny](./media/WpForms/lagg-till-meny.png "Lägg till meny")



## Betalningar - Stripe

Tjänsten Stripe används för att ta in betalningar. WpForms integrerar med Stripe och det finns ett en färdig Stripe-modul som kan användas i formulär. Maila hemsida@ultimatesweden.se om du har frågor kring Stripe.


## Mailutskick - MailChimp

SUF har ett MailChimp-konto som mailadresser automatiskt skickas till om detta sätts upp i WpForms formulär. Maila hemsida@ultimatesweden.se om du har frågor kring MailChimp.
