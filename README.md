# social_media_project
Basic social media project

DB varlık açıklamaları
Özellikler
Kullanıcılar
UserID: Kullanıcıyı benzersiz bir şekilde tanımlayan kimlik.
Username: Kullanıcı tarafından belirlenen benzersiz kullanıcı adı.
Email: Kullanıcının e-posta adresi.
Password: Güvenli bir şekilde saklanan kullanıcı şifresi.
Name: Kullanıcının tam adı.
Bio: Kullanıcının kendini tanıttığı biyografi.
ProfilePicture: Kullanıcının profil fotoğrafı.

Gönderiler
PostID: Her gönderiyi benzersiz şekilde tanımlayan kimlik.
UserID: Gönderiyi oluşturan kullanıcıya referans.
Content: Gönderinin içeriği.
MediaType: Gönderiye eklenen medyanın türü (örneğin resim, video).
MediaURL: Gönderiye eklenen medyanın URL'si.
Timestamp: Gönderinin oluşturulma tarihi.

Yorumlar
CommentID: Yorumları benzersiz şekilde tanımlayan kimlik.
PostID: Yoruma konu olan gönderiye referans.
UserID: Yorumu yapan kullanıcıya referans.
Content: Yorum içeriği.
Timestamp: Yorumun yapılma tarihi.

Beğeniler
LikeID: Beğeniyi benzersiz şekilde tanımlayan kimlik.
PostID: Beğenilen gönderiye referans.
CommentID: Beğenilen yoruma referans (isteğe bağlı).
UserID: Beğeniyi yapan kullanıcıya referans.
Timestamp: Beğeninin yapıldığı tarih.

Arkadaşlık: 
Kullanıcılar arasındaki karşılıklı arkadaşlıkları temsil eder.
FriendshipID (Birincil Anahtar): Her arkadaşlık için benzersiz tanımlayıcı.
UserID1, UserID2 (Yabancı Anahtarlar): Arkadaş olan kullanıcılara ait referanslar.
Zaman Damgası: Arkadaşlığın kurulduğu tarih ve saat.

Mesajlar
MessageID: Mesajları benzersiz şekilde tanımlayan kimlik.
SenderID: Mesajı gönderen kullanıcıya referans.
ReceiverID: Mesajı alan kullanıcıya referans.
Content: Mesaj içeriği.
Timestamp: Mesajın gönderildiği tarih.
