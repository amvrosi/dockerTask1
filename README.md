# Projekt 1
Po włączeniu kontenera w przeglądarce można zobaczyć informacje o kliencie.</br>
Serwer działa na porcie 8888 i zapisuje dane o czasie włączenia, autorze i porcie w pliku logs.txt.</br>
Działanie:</br>
![image](https://github.com/amvrosi/zadanie1docker/assets/133603835/d1d075f1-536d-4809-932c-129695e5091d)<br>
W tym Dockerfile użyto wieloetapowej kompilacji obrazu, dodano Healthcheck, aby sprawdzić kondycję serwera.</br>
Jako obraz bazowy wykorzystano oficjalny obraz python, w obrazie końcowym użyto alpine.</br></br>
Zbudowanie obrazu odbywa się za pomocą polecenia: <b>docker build -t zadanie1docker .</b></br>
![image](https://github.com/amvrosi/zadanie1docker/assets/133603835/65deff36-702f-4aaa-a4c8-5da7f511d9a5)</br>
<b>Uruchomienie kontenera:</b> </br>
![image](https://github.com/amvrosi/zadanie1docker/assets/133603835/1cf0a2e1-8b52-48a9-b70e-a0adebdb2d2e)</br>
<br>
<b>Informacja wyświetlana w pliku logs.txt:</b> </br>
![image](https://github.com/amvrosi/zadanie1docker/assets/133603835/475ca448-c94d-467b-b1d2-b000ec3361f8)
<b>Sprawdzenie warstw obrazu:</b></br>
![image](https://github.com/amvrosi/zadanie1docker/assets/133603835/e8135faf-33f2-40e9-bf74-c9d4f6b063f8)
