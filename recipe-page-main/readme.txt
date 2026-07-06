1.
Do teraz paddingi mi sprawiają problem i musiałem zajrzeć na W3shools jak to się robi
2.
aby zmieniać kolor kropek w liście nienumerowanej - rozwiązanie 
li::marker {
  color: red;
}
3.
aby zmienić rozmiar numerów w liście numerowanej - rozwiązanie
li::marker {
font-size: 12px;
}
4.
aby stworzyć pojedyńcze linie zamiast tabelki
border-collapse: collapse;
aby usunąć ostatni wiersz można
.Nutrition-section tr:last-child
{
      border-bottom: none; ! nie transparent ani background-color: transparent;.........
}