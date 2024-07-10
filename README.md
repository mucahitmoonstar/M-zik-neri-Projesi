# Muzik oneri-Projesi
Girilen müziğin içeriğine  göre müzik  önerisi yapan python projesi

Youtube Api kısmına kendi api girmeniz gerek;

Bu link üzerinden giderek youtube api alabilirsiniz
https://console.cloud.google.com/apis/api/youtube.googleapis.com

kısaca içerikten bahsedeyim;

öncelikle sizden  bir  müzik ismi girmenizi istiyoruz daha sonra bu müziği driveımıza indiriyoruz
indirdiğimiz dosayanın içeriğini wisper modeliyle okuyoruz
sonrasında NLTK ile bazı kelimeleri tokize ediyoruz ve anahtar kelimeleri böyle belirliyoruz
bu kelimelere göre öneriler sunuyoruz.

wisper modeli hakkında daha ayrıntılı bilgi için bu sayfayı ziyaret edebilirisiniz;

https://github.com/openai/whisper

NLTK hakkında daha derin bilgi için burayı okumanızı tavssiye ederim

https://github.com/nltk/nltk

Api nedir bunun için  şu kaynağı önerebilirim;

https://coderspace.io/sozluk/api
