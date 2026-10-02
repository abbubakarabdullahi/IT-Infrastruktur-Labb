# Labbdokumentation
## 1. Titel och introduktion
Namn: Abbubakar Abdullahi
Datum: 2026-09-30
Kurs: Introduktion till yrkesrollen och grunderna i IT-infrastruktur

## 2. Labbmiljö och nätverk
I denna labb så har jag användt mig utav två virtuella maskiner i virtual box, vilket var windows och lubuntu. Jag har konfiguerat båda maskinerina inom samma nätverk för att göra det möjligt för maskinerna att kommunicera med varandra. 

## Nätverkskonfiguration

| Hostname | Operativsystem | IP-adress | Subnätmask | Default gateway   |
|----------|----------------|-----------|------------|-------------------|
| lubuntu-lab | Linux   | 192.168.1.50 | 255.255.255.0(24) | Ingen |
| Skoldator   | Windows | 192.168.1.51 | 255.255.255.0(24) | ingen |
## Kommunikationen mellan Lubuntu och Windows
Jag kontrollerade kommunikationen mellan båda maskinerna genom att pinga, alltså använda ping för att bekräfta kommunikation. Detta innebär alltså att jag pingade från Windows till Lubuntu och vice versa. Kommunikationen bekräftades och blev lyckat på båda fronter.
![Ping från Windows till Lubuntu](images/ping-windows-till-lubuntu.jpeg)
![Ping från Lubuntu till Windows](images/ping-lubuntu-till-windows.jpeg)