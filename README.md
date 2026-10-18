# Formularz rejestracji

Zrobiłem prosty formularz z trzema polami: imię, e-mail i numer telefonu.

Użyłem ConstraintLayout i Barrier.

Barrier ustawia wszystkie pola w jednej linii, nawet gdy etykiety mają różne długości.

Pola mają szerokość 0dp, dzięki czemu rozciągają się do prawej krawędzi.

Każde pole ma odpowiedni inputType:
- Imię – textPersonName
- E-mail – textEmailAddress
- Telefon – phone

Użyłem też Baseline, żeby napisy były wyrównane z polami.

<img width="485" height="825" alt="image" src="https://github.com/user-attachments/assets/b7735064-9c54-4b44-9308-21e062438876" />
