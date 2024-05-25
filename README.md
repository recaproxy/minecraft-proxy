<p align="center">
  <img src="https://github.com/recaproxy/minecraft-proxy/assets/125393057/beeb1b76-1d29-4a0b-b3dc-b3ec5e62d420" />
</p>



# RecaProxy - proxy dla serwera minecraft

### 📌O projekcie

Witaj w projekcie, który narodził się z potrzeby naszego świata cyfrowego!<br><br>
Naszym celem było stworzenie solidnego rozwiązania, które skutecznie zabezpieczy przed powszechnymi atakami DDoS, które niestety stały się codziennością w dzisiejszych czasach.<br>
<br>
Nasz system połączeń, wzbogacony o starannie dobraną technologię filtrów XDP, jest w stanie odeprzeć nawet najpotężniejsze fale ataków. <br>
Dzięki niemu, możemy skutecznie bronić się przed cyberzagrożeniami, zapewniając stabilność i niezawodność naszych usług.

RecaProxy nie tylko skupia się na blokowaniu ataków DDoS, ale również na zapewnieniu kompleksowej ochrony.<br>
Wykorzystujemy zaawansowane mechanizmy walidacji pakietów oraz rate limiting, które pomagają w identyfikacji i eliminacji podejrzanych aktywności (anti-bot).<br> 
Dodatkowo, wprowadziliśmy proces weryfikacji połączeń przez dodatkowe systemy, które wspomagają naszą infrastrukturę w szybkiej reakcji na potencjalne zagrożenia.<br>

Co więcej, nasz system umożliwia również manualną weryfikację przez użytkownika, co daje dodatkową warstwę kontroli nad połączeniami i aktywnościami sieciowymi. 
Dzięki temu, nawet w przypadku bardziej skomplikowanych ataków, użytkownik ma możliwość świadomego monitorowania i interwencji w działania systemu, zwiększając tym samym bezpieczeństwo i kontrolę nad infrastrukturą sieciową.

### 📌TODO

✅ Filtracja pakietów Java Minecraft<br>
✅ Filtracja Wolumetryczna (ataki powyżej 100Gbps)<br>
✅ GeoRouting - kierowanie użytkownika do najbliższego dostępnego serwera w jego okolicy<br>
✅ LoadBalancer - kierowanie ruchu poprzez <br>
✅ Motd Cache<br>
✅ Multi-POP (DE, PL, UK, FRA, CA - via OVH)<br>
✅ Proxy Protocol & TCPShield <br>
❌ Multi-POP Premium (another location via interconnect Equnix)<br>
❌ Weryfikacja Anty-Bot (wkrótce)<br>
❌ Statystyki ruchu | ataków<br>
❌ Panel Konfiguracyjny dla beta-testerów.<br>


### 📌Działanie
Projekt jest w trakcie przygotowywania.

# RecaProxy - rate limiting 

### 📌Wprowadzenie

Ograniczanie połączeń przy użyciu PPS Limit polega na monitorowaniu i regulacji liczby pakietów przesyłanych na sekundę do serwera lub aplikacji. <br>
<br>
Dzięki temu mechanizmowi można precyzyjnie kontrolować obciążenie sieciowe, zapobiegając przeciążeniu serwerów oraz zapewniając stabilne i wydajne działanie aplikacji.<br>
Recaproxy pozwala na ustawienie określonego limitu pakietów na sekundę, co skutecznie chroni infrastrukturę przed atakami DDoS oraz zapewnia równomierne rozłożenie ruchu sieciowego.<br>

### 📌Limt nadmiernych połaczeń do serwera [OVH Bypass & OVH AMP & DNS
<p align="center">
  <img src="https://i.imgur.com/BTbMnZn.png" />
</p>

### 📌Limt nadmiernych połaczeń do serwera [OVH Bypass & OVH AMP & DNS + walidacja pakietów

<p align="center">
  <img src="https://i.imgur.com/HMsZqE6.png" />
</p>
