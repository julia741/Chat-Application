
Basic Chat Application with firebase




Funkcje: 
Rejestracja oraz logowanie,
Przesyłanie wiadomości między użytkownikami,
Wyświetlanie listy zarejestrowanych użytkowników,
Wyświetlanie wiadomosci.
Walidacja (hasło,email, błąd wysyłania pustej wiadomości)


Technologie:
Firebase database, 
Firebase authentication 

//////BAZA DANYCH FIREBASE////

Users – Zarejestrowani użytkownicy
Chats – Wysłane wiadomości(nadawca,odbiorca)

///////STRONA STARTOWA///////
![startactivity](https://user-images.githubusercontent.com/73189357/115951670-38f3d480-a4e2-11eb-93cc-0423bc9ac57a.png)


Buttony przekierowują na strony:Logowanie,rejestracja:

![Login](https://user-images.githubusercontent.com/73189357/115951652-1c579c80-a4e2-11eb-990c-eefd433f81ae.png)
![Register](https://user-images.githubusercontent.com/73189357/115951663-2da0a900-a4e2-11eb-8d7b-95f50b7ac157.png)


![walidacja](https://user-images.githubusercontent.com/73189357/115951775-dc44e980-a4e2-11eb-930b-ff68ae10fccb.png)
Formularz rejestracji sprawdza, czy email ma odpowiedni format
a hasło składa się z min. 6 znaków. Po pomyslnej rejestracji, aplikacja przekierowuje nas na stronę logowania.

![logdontwork](https://user-images.githubusercontent.com/73189357/115952734-08af3480-a4e8-11eb-9290-1bf7c7b84911.png)

Zalogowac się może tylko zarejestrowany użytkownik.


![users](https://user-images.githubusercontent.com/73189357/115951793-fb437b80-a4e2-11eb-8ceb-cecf4b6134a1.png)
AcctionBar pozwala przełączać się między rozmowami a listą użytkowników.
Lista użytkowników to lista zarejestrowanych użytkowników. Wyswietla on także nazwę aktualnie zalogowanego użytkownika, avatar, który ustawiony jest na domyślny. Po kliknięciu w trzykropek pojawia się opcja "Logout", która pozwala na wylogowanie oraz powrót do strony startowej.

![mess](https://user-images.githubusercontent.com/73189357/115954321-998a0e00-a4f0-11eb-80fb-005cf333983d.png)

Po kliknięciu na nazwę danego użytkownika wyświetla się widok chatu.Wiadomości zapisują się w bazie danych.

