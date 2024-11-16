# Chatbot-projekti

Tämä chatbot käyttää OpenAI:n API-rajapintaa vastatakseen käyttäjän kysymyksiin luonnollisella kielellä. Vaikka projekti ei tällä hetkellä ole toiminnassa (koska OpenAI:n maksullinen avain ei ole voimassa), se toimii silti demonstraationa siitä, miten tekoäly- ja API-teknologioita voidaan hyödyntää ohjelmoinnissa.

## Ominaisuudet
- **OpenAI:n API-integraatio:** Hyödyntää GPT-rajapintaa keskusteluun käyttäjän kanssa.
- **Helppo laajennettavuus:** Projektissa on selkeä rakenne, jota voi käyttää muiden API-avaimien kanssa tai kehittää lisää.
- **Käyttäjäystävällisyys:** Helppo käynnistää ja käyttää komentoriviltä.

## Kuinka käyttää projektia
1. Hanki OpenAI:n API-avain (ohjeet: [OpenAI API](https://platform.openai.com/signup/)).
2. Lisää avain projektin ympäristömuuttujaksi `.env`-tiedostoon seuraavasti:
OPENAI_API_KEY=your_api_key_here

3. Asenna tarvittavat riippuvuudet:
pip install -r requirements.txt

4. Aja chatbot seuraavalla komennolla:
python chatbot.py

## Huomio
Projektin nykyinen versio ei toimi ilman voimassaolevaa OpenAI:n API-avainta. Voit kuitenkin tutustua koodiin ja käyttää sitä pohjana uusille projekteille.
