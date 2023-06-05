![xxx](https://github.com/erknakbs/bookstore_react/assets/105823500/dc115b83-8458-4937-b437-fb30778a2f95)


-----------------------------

Create Read Update Delete

Create Arrow Edit Delete

Include bootstrap in project > Add bootstrap cd to index.html
1- Create a form to get the new element to be added: get the data from the form and transfer the state button, as soon as the button is pressed, create a new object together with the information entered in the form. reset
2- Get the books held in the books state and list them with the map method (press to the screen) > if the state is empty, write "no book has been added yet" to the screen > Send book information to the BookCard component as a prop > Show all the book-related features of the BookCard component
3- Deleting a Book: > when the delete button of any book is pressed > let the id of the one to be deleted go to the running function > take the incoming id as a parameter to the function > take the objects that are not equal to the id to be deleted and transfer to an array > transfer the resulting array to state
<li>
     4- Mark Book as Read:
     > send the book to the running function when the read button is pressed
     > reverse the isRead of the book
     > find the element to change in the array
     > remove that element and add a new one in its place
</li>

<li>
     5- Do the Editing:
     > When the Edit button is clicked, a modal will appear on the screen.
     > and import the book to be edited into app.jse (editItem)
     > In Modal: An input to change the book name
     > updates the editItem variable every time the input changes and passes it to app.jse
     > Cancel Button > Closes Modal
     > Save Button > Runs handleEditBook in app.js
     > running function removes old element from array and replaces it with new one
</li>
----------------------------------

<h1>CRUD App</h1>
<p>Create Read Update Delete</p>
<p>Oluştur Oku Düzenle Sil</p>

<ul>
    <li>
        Projeye bootstrapi dahil et
        > index.htmle bootstrap cdni ekle
    </li>
    <li>
        1- Yeni eklenicek elamanı almak için form oluştur:
        form içserisinden gelen verileri al ve state aktar
        ekle butonuna basıldığı anda forma girilen bilgilerle beraber yeni obje oluştur
        oluşturulan objenin değerleri: tarih, kitapIsmi, id, okunduMu
        oluşan objeyi kitaplar isminde bir diziye aktar
        obje oluşturulduktan inputu sıfırla
    </li>
    <li>
        2- books Stateinde tutulan kitapları al ve map methodu ile listele(ekrana bas)
        > eğer state boşsa ekrana "henüz kitap eklenmedi" yaz
        > BookCard bileşenine kitap bilgilerini prop olrak gönder
        > BookCard bileşenin kitapla iligli bütün özellikleri göster
    </li>
    <li>
        3- Kitap Silme: 
        > herhangi bir kitabın sil butonuna basıldığında 
        > çalışan fonkisyona silinicek olanın idsi gitsin
        > gelen idyi fonkisyona parametre olaraka  al 
        > silinicek id ye eşit olmayan objeleri al ve bir diziye aktar
        > oluşan diziyi state aktar
    </li>

    <li>
        4- Kitabı Okundu Olarak işaretle:
        > okundu butonuna basılınca çalışan fonkisyona kitabı gönder
        > kitabın isRead değerini tersine çevir
        > dizi içerisinde değişecek olan elemanı bul
        > o elemanı çıkar ve yerine yenisini ekle
    </li>

    <li>
        5- Düzenleme İşlemini Yap:
        > Düzenle butonuna tıklanıdğında ekrana bir modal çıksın
        > ve düzenlenicek kitabı app.jse aktarsın (editItem)
        > Modalda: Kitap ismini değiştirmek için bir input
        > input her değiştiğinde editItem değişkenini günceller ve app.jse aktarır
        > Vazgeç Butonu > Modalı Kapatır
        > Kaydet Butonu > app.jsde bulunan handleEditBook çalıştırır
        > çalışan fonkisyon diziden eski elemanı çıkarır yerine yenisini koyar
    </li>

</ul>
