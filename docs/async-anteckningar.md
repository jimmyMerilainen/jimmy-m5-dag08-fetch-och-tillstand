### Steg 2

Hur fungerar falskFetch?
falskFetch simulerar ett API-anrop genom att returnera ett eget JSON-svar och en statuskod. Den sparar också vilken URL som anropas.

Varför testa med en falsk fetch istället för den riktiga?
För att kunna testa både lyckade anrop och fel utan internet eller ett riktigt API. Det gör testerna snabbare och mer förutsägbara.
