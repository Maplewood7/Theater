## 📝 About

<div align="justify">
Notes is a web app for creating, deploying and sharing notes. Easly manage and organize
all your notes so you can share them with other Notes partners.
</div>

## ⚙️ Features

### Guests 👥

```
+_____________________________+
| Blok   | Notes  |    Editor   |
|_____________________________|
|        |        |                |
|        |        |                |
|        |        |                |
.        .        .                .
.        .        .                .
```

<!-- As they cannot save changes and are limited to sessions, Guests work on one 
Blok. They may have as much Notes as they wish. They are limited to Print or Export
to PDF, seperate Notes or a whole Blok (no sharing). They may use all the tools for
typography (fonts, colors, bullets, lists, spell check). They may import tables, files,
pictures, URL-s, symbols to their Notes. Drawing is also enabled. -->

- have one Blok
- export Blok/Notes to PDF
- are limited to Guest Editor features
- are limited to the duration of the session

### User 👤

```
+_____________________________+
|       Blok       |               |
|_____________________________|
| Section | Notes  |  Editor    |
|_____________________________|
|        |        |                |
|        |        |                |
|        |        |                |
.        .        .                .
.        .        .                .
```

- may have many Bloks
- are able to share Bloks and Notes 
- may enable syntax checking

### Example User Story 🗣️

> Must be formatted like so:
> > "As a user.."  
> > "As a document creator.."

<div align="justify">
Svaki korisnik ima svoj račun, koji sadrži bilješke (notes) i obavijesti (notifications)
koje može prilagoditi prema vlastitim potrebama. Bilješke i obavijesti mogu biti međusobno
povezane u odnosu više-na-više, što znači da jedna obavijest može biti povezana s više
bilješki i obrnuto. Također, korisnik može dijeliti određenu kombinaciju bilješki i obavijesti
s drugim korisnicima.    
Uz to, korisnicima bi se omogućilo organiziranje sadržaja u različite kategorije, kao
što su "Faks", "Posao", "Osobno" i slično, kako bi lakše upravljali svojim informacijama.  
Planirana je i implementacija mogućnosti personalizacije vizualnog sučelja, poput 
prilagodbe boja koje odgovaraju korisniku, promjene fontova, a uz dovoljno resursa, 
razmatra se i dodavanje osnovnih tema za izgled sučelja. Primjerice, korisnici bi mogli
birati između zaobljenih i kutastih elemenata dizajna.  

The user logs in to their account 
(or creates one). A selection of templates is offered upon login. If 
the user does not select a template, he is sent to an empty template predefined
in the application. The user is able to print the created file, save it as a
pdf or share it with other users.  
The main screen is divided into paragraphs, pages and an editor.  
Inside the editor, all basic functions for text manipulation are enabled -
font formatting, lists, styles and syntax checking.  
It is possible to add tables, files, images, links, symbols, emoticons and sound.  
The user is able to view all created paragraphs, search and delete them.
</div>

## 🗄️ Database

Model baze.
Tablica:

Korisnici (Users),

Bilješke (Notes),

Obavijesti (Notifications),

Kategorije (Categories),

Povezanost Bilješki i Obavijesti (Note_Notification),

Dijeljeni sadržaji (Shared_Items),

Teme (Themes),

## 📌 Tasks

1. README ⌛️

Boris:  
- (README) List out features for Guests and Users ⌛️
- (README) Create an example Database ⌛️

Silvestar:  
- (personal) Set-up working environment (IntelliJ IDEA and Git) ⌛️
- (README) Write an Example User Story ⌛️

## 🎓 Authors

Developed by [*chora7*](https://github.com/chora7) and [*salveta96*](https://github.com/salveta96).

## ⚖️  License

For more information check the [LICENSE](LICENSE) file.
