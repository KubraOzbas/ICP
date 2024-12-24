# KİŞİSEL BİLGİLER
Ben Kübra Özbaş. Afyon Kocatepe Üniversitesi - Bilgisayar Programcılığı (2022) mezunuyum. Henüz aktif bir projede yer almamakla birlikte önemli workshoplara katılarak kendimi alanımda geliştirmeye çalışıyorum.


# ICP WWORKSHOP
Bu proje Patika.Dev-ICPHubTurkey tarafından düzenlenen ve Yusuf Utkurak moderatörlüğünde oluşturmuş olduğum; Motoko dilinde yazılmış bir telefon defteri ve mesaj geçmişi yönetmek için kullanılan bir aktör(actor) tanımlanmış bir çalışma projesidir.

##Tanımlamalar:
Name ve Phone: İsim ve telefon numarası için metin (Text) türünde tipler.

Entry: İçerisinde açıklama (desc) ve telefon numarası (phone) olan bir kayıt türü.

Message: Alıcı (receiver) ve mesaj içeriği (mess) olan bir mesaj türü.

##Veri Yapıları:
phoneBook: Anahtar olarak isimleri (Name), değer olarak kayıtları (Entry) saklayan bir HashMap (telefon defteri).

MessageHistory: Anahtar olarak telefon numaralarını (Phone), değer olarak mesajları (Message) saklayan bir HashMap (mesaj geçmişi).

##Fonksiyonlar:
insert: Bir isim ve kayıt alır ve bu bilgiyi telefon defterine ekler.

sendMessage: Bir telefon numarası (gönderenin telefonu) ve mesaj alır ve bu bilgiyi mesaj geçmişine ekler.

getPhone: Bir isim alır ve bu isme karşılık gelen kayıt bilgisini (eğer varsa) döndürür.

getMessage: Bir telefon numarası alır ve bu numaraya karşılık gelen mesaj bilgisini (eğer varsa) döndürür.
