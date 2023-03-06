Kreiranje Angular aplikacije na kursu Napredno Web Programiranje.
Aplikacija je stock-market i osmisljena je da predstavlja neku berzu gde imamo firme, pa svaka firma ima svoje akcije koje imaju svoje cene...
Kroz kurs su obradjene sledece teme: Angular komponente, zatim Angular direktive gde smo vezivali neke funkcionalnosti za html elemente (structual directives, atribute directives).
Nakon toga -  Template Driven forms i Angular services. Njih smo uveli jer smo hteli da omogucimo da pomocu servisa vezemo komponente sa nekim Restful API-jem i prvo smo to radili tako sto smo u te servise stavljali mockup podatke dok sama forma koju smo kreirali nije imala znanje o tome da ona zapravo ne komunicira sa Restful servisom vec sve ide lokalno. Kod servisa smo se upoznali sa princimo dependency injection gde smo injektovali te servise na nivo cele app a potom i na nivou komponenata.
Zatim smo kreirali server koji ima Restful API na srednjem sloju i podigli ga pomocu Node - jedina stvar koja nas je tu zanimala je kako sa frontenda da se nakacimo na njega a u detalje njegove implementacije nismo ulazili.
Uveli smo HTTP Client jer nismo hteli vise lokalno da cuvamo mockup-ovane podatke vec preko http-a da ih saljemo na server.
Prosli smo i Observables (asinhone operacije) kao i Input/Output decorators, HTTP headers i Interceptors.
I na samom kraju Rutiranje koje nam omogucava navigaciju od jedne do druge komponente. 

[Development server]
Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.
