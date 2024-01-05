# dyfi.py

Yksinkertainen windowsin tehtävien ajoituksessa ajettava dy.fi domain päivitin. dyfi.py vaatii
toimiakseen python3 ja [Requests](http://docs.python-requests.org/en/latest/)
kirjaston

Oletus editori on visual studio code. Vaihda tarvittaessa vaikka notepadiin, jos et halua codea asentaa.

## Ensimmäinen ajo komentoriviltä domainin lisäämiseksi cfg tiedostoon

    # python dyfi.py --add
    Käyttäjä: kalle.kayttaja@esimerkki.fi
    salasana: salasana123
    Domain nimi: host.dy.fi
    # python dyfi.py -u

## Nimen lisääminen

    # dyfi.py --add

ja syötä käyttäjä, salasana ja dy.fi nimi kysyttäessä.

## Muokkaus

    # dyfi.py --edit

dyfi.py avaa oletus editorin (ympäristömuuttuja EDITOR) tai 'code' jos EDITOR
muuttujaa ei ole asetettu

## Käyttö

Luo uusi tehtävä windowsin tehtävien ajoitukseen (task scheduler)

Anna tehtävälle nimi: dy.fi osoitteen päivitys  
Kuvaus: Päivittää dy.fi palvelun domainin ip osoitteen  
Suorita riippumatta siitä, onko käyttäjä kirjautunut sisään  

Lisää käynnistin  
Aloita tehtävä: Ajoituksen yhteydessä  
Asetukset: Päivittäin, Käynnistä seuraava päivä klo 00:01, Toista joka 1 päivä  
Toistamisväli 1 tunti, kesto määrittämätön  
Käytössä (x)  

Luo uusi toiminto  
Toiminto: käynnistä ohjelma  
*Huom! esim.*  
Ohjelma tai komentosarja: "C:\Python38\python.exe"  
Lisää argumentteja (valinnainen): "C:\GIT\dyfi.py\dyfi.py" -u  
*Muokkaa vastaamaan varsinaisia kohteita*  

Muihin asetuksiin ei välttämättä tarvitse koskea.

