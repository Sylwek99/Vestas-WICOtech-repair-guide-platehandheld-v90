

# Vestas-WICOtech-repair-guide-platehandheld-v90
Instrukcja naprawy panelu ręcznego do turbiny Vestas (wicotech)
jeli pojawia się taki komunikat na panelu 
<img width="590" height="442" alt="IMG_8506" src="https://github.com/user-attachments/assets/59217448-f37f-4fca-847d-70f98180f155" />
to prawdo podobnie uległ uszkodzeniu pamięc programu 
<img width="366" height="488" alt="Zrzut ekranu (47)" src="https://github.com/user-attachments/assets/173b0164-9139-419d-943e-89793b72c9c9" />
na początek odczytałem pamięc tego układu za pomoca arduino mega 2560 
program jest pod tytułem ,,vestasodczytpamieci,, wgraj go zanim podłaczysz kosc pamięci pin aut 
<img width="388" height="602" alt="Zrzut ekranu (51)" src="https://github.com/user-attachments/assets/72d6cfb0-59dc-4f9b-8900-bf18b4d11ce8" />
<img width="399" height="453" alt="Zrzut ekranu (50)" src="https://github.com/user-attachments/assets/2449db5c-c94c-4f1f-b637-ffa1f82aadae" />
<img width="405" height="316" alt="Zrzut ekranu (49)" src="https://github.com/user-attachments/assets/9ca10075-9bfc-4add-9db9-530360a3be35" />
<img width="399" height="555" alt="Zrzut ekranu (52)" src="https://github.com/user-attachments/assets/0bf651e6-6d40-49f7-91a5-4d0d9d014c9c" />
nastepnie w monitorze portu szeregowego wpisz komęde ,,START,, pojawi ci się odczyt z pamięci 
nastepnie przekopjuj kod i wklej go do notatnika 
nastepnie odczytaj pamięc jeszcze raz i wklej odczyt do notatnika 
nastepnie pobierz program z internetu do porównywania takich danych np ,,,HxD,,,
jesli mimo odczytoów jednym po drugim programy się rózni to znaczy że kosc lub program jest uszkodzony ale w moim przypadku 
udało mi się wgrać program do uszkodzonego modułu i działa 

żeby to naprawić wgramy nowy program. z mojego notatnika tod tytułem (zrzut) pochodzi ten plik z drugiego sprawnego panelu 


<img width="1320" height="1031" alt="Zrzut ekranu (43)" src="https://github.com/user-attachments/assets/da784b0c-ca59-480c-ba5a-abf85b5c28ed" />
jak widzisz musiałem usunąc adrey pamieci żęby latwiej się wgrało za pomoca python  
wsad pochodzi od sprawnego panela 
zebys mugł to wgrac (zrzut) potrzebujesz arduino mega 2560 mega i wgranego programu do niego pod tytułem (kod pośredni do arduino mega 2560) 
zapamietaj na którym porcie masz arduino bedzie to potrzebne u mnie jest to port 'COM7' nastepnie zamknii srodowisko arduino (i monitor portu szeregowego. (o ile go wcesniej otwierałeś )
<img width="980" height="876" alt="Zrzut ekranu (45)" src="https://github.com/user-attachments/assets/51c3b7c7-1393-4c4d-80a5-d73ab3692bb8" />
teraz utwórz nowy folder pod nazwa Vestas na pulbice otworz notatnik i wklej (zrzut) zapisz jako  go pod tytułem zrzut.txt (upewnij sie ze plik tak sie nazywa) 
nastepnie w tym samym folderze otwurz nastepny notatnik i skopiuj kod (program python) i zmien nr portu jesli msza inny  port zapiz jako z końcówka .py  a nie txt !!!
teraz jak to uruchomić  
1 otworz folder Vestas
w gorne pole sciezki C:\Users\xxx\Desktop\Vestas usun to i wpisz Cmd 
<img width="1223" height="482" alt="Zrzut ekranu (46)" src="https://github.com/user-attachments/assets/ca87047b-be46-4aab-9dc4-2afd52a9591c" />

wyswietli ci sie konsola CMD nastepnie wpisz tam : python wgraj.py i wcisnij  enter 


