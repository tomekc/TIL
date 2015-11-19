## Techniques

### Consumer-driven contract testing

Testowanie z żywymi serwisami: kruche
Dublerzy: w końcu się rozsynchronizują z prawdziwym serwisem
CDC są obowiązkową częścią portfolio testów mikroserwisów.

### Decoupling deployment from release

Wrzucamy do infrastruktury artefakty w momencie kiedy spełniają kryteria jakościowe. Biznesowy _release_ ma miejsce w momencie przełożenia "wajchy" i odblokowania ficzerów. 

### Products over projects

Realizacja projektu, planowanie na _n_ sprintów, a potem 3xZ: zamiatamy, zamykamy i zapominamy.
Praca nad oprogramowaniem powinna być nieustannym wysiłkiem, którego należy zaprzestać dopiero w momencie, kiedy jej wytwór przestaje być potrzebny.

### Backends For Frontends

Już to robimy.

### Idempotency filters

Zabezpieczyć się przed wielokrotnym wywołaniem serwisu nieidempotentnego, przykładowo na skutek opóźnień i konfiguracji load-balancerów.

### Backends for frontends (Trial)

### Idempotency filters (Trial)

## Tools

### Moutebank

For mocking and stubbing network services


