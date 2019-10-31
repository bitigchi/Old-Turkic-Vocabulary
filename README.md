*This is a project mirror for the original database hosted [here](https://www.dolthub.com/repositories/bitigchi/old-turkic-vocabulary). Pull requests are welcome from here as well.*

# Old Turkic Vocabulary

This project aims to gather vocabulary of the Old Turkic language used until the end of 9th century, including the era of Göktürk and the Uyghur Khaganate.

Initial project aim is to gather the words in their original spelling, transliteration, and Turkish translation.

To contribute, fork the Dolt database from the link above, and send pull requests. Alternatively, you can fill out the CSV file as shown below, then send it/create a pull request here.

| ot_word | ot_transliteration | tr_translation | en_translation | word_class |
| ------- | ------------------ | -------------- | -------------- | ---------- |
| 𐰉𐰆𐰑𐰣    | bodUn              | boylar         | tribes         | noun       |

## Typing Guide

* Use original Old Turkic tamgas/runes.
* If available, Uyghur-era spelling is preferred.
* Transliteration is indicated via lowercase letters. If a vowel is not shown in the runic script, it is indicated via a capital letter in the Latin transliteration.
* `tr_translation` is a required field. If you do not speak-know Turkish, feel free to enter a duplicate `en_translation`, we'll sort them out.

If you have SQL knowledge, and have experience in creating dictionaries, feel free to reach out to me; any technical help is always welcome.
