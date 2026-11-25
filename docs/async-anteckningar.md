### Steg 2

Hur fungerar falskFetch?
falskFetch simulerar ett API-anrop genom att returnera ett eget JSON-svar och en statuskod. Den sparar också vilken URL som anropas.

Varför testa med en falsk fetch istället för den riktiga?
För att kunna testa både lyckade anrop och fel utan internet eller ett riktigt API. Det gör testerna snabbare och mer förutsägbara.

### Steg 8

Ändra "data/meny.json" till "data/finns-inte.json"
Något gick fel: Unexpected token '<', "<!DOCTYPE "... is not valid JSON

Töm meny.json till [] och se tomt
Inga rätter hittades.
