# f(x) = e^(-x/4) · arctan(x)

## Vis at toppunktet er gitt ved arctan(x) - 4/(x²+1) = 0

For å finne toppunktet setter vi f'(x) = 0. Vi deriverer med produktregelen:

$$f'(x) = -\frac{1}{4}e^{-x/4} \cdot \arctan x + e^{-x/4} \cdot \frac{1}{x^2+1}$$

Trekker ut $e^{-x/4}$ (som aldri er 0):

$$f'(x) = e^{-x/4}\left(\frac{1}{x^2+1} - \frac{\arctan x}{4}\right)$$

Siden $e^{-x/4} > 0$ for alle $x$, er $f'(x) = 0$ bare når parentesen er 0:

$$\frac{1}{x^2+1} - \frac{\arctan x}{4} = 0$$

Ganger med 4 og omorganiserer:

$$\arctan x - \frac{4}{x^2+1} = 0 \quad \blacksquare$$

---

## Toppunktet numerisk

Løser likningen numerisk (se `numerisk.ipynb`):

$$x^* \approx 1.6922, \qquad f(x^*) \approx 0.6797$$


## PS!
KI er brukt for å formatere svaret mitt litt mer formelt, men den løser IKKE problemet for meg.
Den legger heller ikke noe essensielt til i forklaringen som jeg allerede ikke hadde med, men kanskje omformulert det litt annerledes.
kun slik at den er mer lesebar og formelt. og strukturert det slika t matte delen er sentrert.

Jeg skriver også matten min i latex dersom det er mer effektiv med tanke på innlevering, og fordi jeg øver på å bli bedre på det.


Jeg fikk heller ikke til å kjøre koden min i jupyter labs, men det var kun fordi jeg ikke hadde lastet ned matplotlib i det env jeg kjører koden min inni
så selve den numeriske utregningen og plottingen er riktig, eller bør være det. jeg bruker bare ikke notebooks så ofte, og det er litt styr med arch linux + jeg var litt kort på tid.
