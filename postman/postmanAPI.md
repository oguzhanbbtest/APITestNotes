 # POSTMAN ILE API TESTİ
 

 Postman kurulum adımlarını tamamladıktan sonra yeni bir collection oluşturalım ve request ekliyelim.

![](postmanimage/postmancreatecollect.png)

Enter the request URL kısmına çalışacağımız link'i ekleyelim
        
        https://reqres.in/api/users?id=3

![](postmanimage/postmangetreq.png)

GET methodumuzu seçtikten sonra send butonu ile etkileşime girdiğimizde body kısmında sorgumuzun JSON formatlı çıktısını görmüş olucağız.

![](postmanimage/postgetmethod.png)

POST methodu ile apimizde veri oluşturalım
![](postmanimage/postmanepost.png)

DELETE methodumuz ile oluşturduğumuz veriyi silebiliriz.
![](postmanimage/postmandelete.png)

Global bir değişken oluşturalım ve ismine URL diyip url'imizi içine atalım.

![](postmanimage/postmanaddGlobvariable.png)

Enter request URL kısmına gelip süslü parantez yazdığımızda "{" oluşturulmuş tüm variableları görebiliriz

![](postmanimage/postmanseevariable.png)

Oluşturduğumuz tüm sorguları otomatize koşmak için Collection kısmında run collections seçeneği ile yapabiliriz.
![](postmanimage/runcollection.png)




 

