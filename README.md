# Send a Message to the ActiveMQ Queue
## _Use Cases_
Transactional Messaging
Clustering and Asynchronous messaging model
Streaming of Data

ActiveMQ, java ile yazılmış open-source bir message broker uygulamasıdır. JMS (Java Message Service) uygular.
JMS API ile yazılımlar arasında mesajlaşmayı sağlar ve senkron yada asenkron olarak çalışabilen bir arayüzdür.

Localinizde ActiveMQ ilk defa indiriyorsanız eğer çalışıp çalışmadığını anlamak için  " http://localhost:8161/ "kontrol edebilirsiniz.
Açılan ekranda "Manage ActiveMQ broker" seçeneğini seçtikten sonra kullanıcı adı ve şifre için "admin" yazabilirsiniz. Default olarak gelen bu şekildedir. Giriş yaptıktan sonra dashboardda queueları producer ve consumerleri görüntüleyebilirsiniz.

Bu repository örnek olarak activemq message sending uygulamasıdır. İndirdikten sonra localinizde test edebilir ve inceleyebilirsiniz.
Öncelikle Producer Queue üzerine publish edecek ve Consumer bu mesajları ActiveMQ üzerinden dinleyecektir.