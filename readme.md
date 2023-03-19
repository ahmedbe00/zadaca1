Od danas zadace ce cesto biti neki zadatci koje trebate rijesiti, googlati istrazivati.
Za pocetak bi vas zamolio da uradite sljedece:
1. Napravite repozitorij “zadaca1”
2. Zatim cete otvoriti intelij
3. Ici cete na ‘File’ -> ‘New’ -> ‘Project’
4. Setujte ime ‘zadaca1’
5. Location setujte path unutar kloniranog repozitorij-a.
   npr. Ako je vas repozitorij u c:\workspace\ onda ga stavite tu.
   inace je praksa da svi projekti budu u nekom “workspace” folderu.
6. Kliknite ‘Create’
   Trebali bi sada imati c:\workspace\zadaca1
   Terminalom otidjite u taj folder
   udjite u : /c/workspace/zadaca1
   zatim uradite
   git init
   git add .
   git commit -m "Initial commit"
   git remote add upstream https://github.com/Foo/zadaca1.git  (HTTPS clone link vaseg repozitorija koji kopirate sa github-a)
   git push origin main
   Neki od vas imaju problema sa branchevima naime git init vam napravi da je lokalni branch master , dok je na github-u main
   Ukoliko vam je na github glavni branch main a lokalno master ovo ce reimenovat lokalni glavni branch u main pa necete imati problema sa pushanjem
   git branch -m master main
   Ako budete imali problema kontaktirajte me
8. Ukoliko zelite da pokrenete projekat najlaksi nacin je da idete:
   ‘vasProjekat’ u browseru intellij sa lijeve strane -> ‘src’ folder
9. Main klasa koja sadrzi ' public static void main’ metodu
10. Desni klick na ' public static void main’ metodu i izaberite -> Run ‘Main.main’
11. Od tog trenutka mozete da pokrecete projekat sa onim malim play dugmetom
    
Zadaca:
1. Napravit cete readme.md file koji sadrzi zadatke koje sam vam zadao. Ovo mozete preko intelij ne terminala.
2. readme.md fajl se treba nalaziti u samom folderu zadaca1
3. Kada zavrsite sve uradite
   git add .
   i pushajte vas kod na repozitorij
4. Probajte da dodjelite jednu varijablu jednog tipa u drugu varijablu drugog tipa i zakljucite koje kombinacije se ne mogu dodjeljivati jedne u druge npr :
   String someText = "Some random text"
   int someNumber = someText;
   Pogledajte koju gresku javlja i zasto vam javlja gresku.
   Zatim zakomentarisite obje linije koda.
5. Deklarisati varijable za: Ime i prezime, prvo slovo imena, godina rodjenja, broj 100 000 000 000, broj 42.001
   imena moraju biti smislena i na engleskom.
   6.Isprintate vase ime koristeci samo brojeve  koji se pretvore u char-ove.
7. napravite vaijablu koju kad ispisete ispise tekst:
   Answer to the Ultimate Question of Life, the Universe, and Everything is the number 42: true
   ili
   Answer to the Ultimate Question of Life, the Universe, and Everything is the number 42: false
8. Zelim da mi napisete program koji ce poceti sa tekstom:
   This is a number xxx and it is about to double;
   I zatim 8 puta da se udupla njegova vrijednost i svaki put da se isti tekst ispise
   sa uduplanim brojem. PRvi put kad se ispise broj mora biti izvorno upisani broj.
   xxx je neki broj koji mogu ja sam da dodam a da se ne narusi logika.
   BONUS: (ko zeli)
   Da se za svako duplanje ispise poruka nakon glavnog teksta
   The original number has been doubled: XXXX times. (Za 4 duplanja)
   The original number has been doubled: X times. (Za 1 duplanje)
   The original number has been doubled: XXXXXXXX times. (Za 8 duplanja)
   Napomene, potrudite se da kod bude uredan, vidjeli ste onu opciju format code,
   meni je u ovoj fazi bitno da code radi, pricat cemo o optimizacijama itd.
   Vas zadatak je da napravite da ovo cudo radi :D :smile:
   Ako vam treba pomoc, naravno prvo komitajte sav kod pushajte da pa mogu da vidim vasu izradu da vam mogu pomoci.
   Ah da NAPOMENA, morate koristiti samo ovo sto ste ucili samnom, nista advanced, petlje , lupovi, metode…. ono sto smo presli je ono sto smijete koristiti