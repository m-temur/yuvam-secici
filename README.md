# yuvam-secici

[Yuvam](https://github.com/m-temur) uygulamasında eşin Eve katılırken paylaşılan tabloyu bir kez seçtiği Google seçici sayfası.

Yuvam, Google Drive'a yalnızca `drive.file` izniyle erişir. Bu izin, başkasının oluşturup paylaştığı bir dosyayı ancak kullanıcı onu Google seçicisinde seçtiğinde açar. Bu sayfa o seçimi yaptırır; başka bir veri toplamaz veya saklamaz.

Adres: https://m-temur.github.io/yuvam-secici/
İsteğe bağlı parametreler: `?klasor=<paylaşılan klasör kimliği>&eposta=<Google hesabı>`

`config.js` içindeki API anahtarı gizli değildir; Google Cloud'da yalnızca Google Picker API'ye ve bu siteye kısıtlıdır.
