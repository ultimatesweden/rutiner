# IT

SUF använder följande IT-tjänster/system:

* Github - hemsida, projektdokumentation etc.
* GSuite - gmail-konton, mail-grupper, Google Drive
* SpeedLedger - bokföring
* Wordpress/WooCommerce - hemsida och webshop (under uppbyggnad)
* WebEx (använder SFF:s konto)
* Amazon Web Services (använder SFF:s konto)
* YarkonS3

Alla i styrelsen har ett gmail-konto under ultimatesweden.se. Dessa konton används för att skapa konton hos de tjänster som 
styrelsemedlemmar och andra som arbetar åt SUF behöver. ultimatesweden.se mailen kan t.ex. användas för officiella mail. Det gör det också enkelt att administrera användare när styrelsemedlemmar tillkommer och slutar.


## Github

Dessa rutine-sidor ligger på github-kontot ultimateasweden.


## Google Drive

När en ny styrelse tillträder efter årsmötet skapas en Team Drive i Google Drive som alla i styrelsen får tillgång till. Med en team drive per styrelse är det enkelt att styra vem som ska ha tillgång till vad.

Team Drives används även för arbetsgrupperna vid behov (säg till styrelsen vilka som ska ha tillgånbg). 


## Elektroniska signaturer

### DocuSign

SFF har ett DocuSign konto som grenförbunden kan använda. Maila dokument som ni vill få signerade till kansliet@frisbeesport.se and ange vilket som ska signera samt vilka email-adresser de har.


### Kivra

Kivra har stöd för elektroniska signaturer med BankID vilket ska fungerar för att signera årsredovisningar.


## Bildarkiv

Bilder sparas i AWS S3 buckets. Det finns en bucket för material som SUF har rättigheterna till och därmed kan användas fritt. En annan bucket anväds för material där SUF inte har fulla rättigheter och därmed endast får användas efter godkännande av de som har rättigheterna. Materialet är organiserat i en katalog per år och där under en katalog per event.

[s3-bucket-listing](https://github.com/rufuspollock/s3-bucket-listing) används för att göra materialet publikt.

[Länk till bildarkiv](http://ultimatesweden-bildarkiv-public.s3-website.eu-north-1.amazonaws.com/)
