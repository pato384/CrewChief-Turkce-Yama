# Crew Chief Türkçe Yama (topluluk yaması)

Kurucu: **pato384**

Crew Chief V4 (4.19.5.8) için Türkçe şef ve spotter sesleri, Türkçe menüler ve Türkçe sesli komutlar. Le Mans Ultimate ve Assetto Corsa Competizione'de denendi.

## [İndir: Crew Chief Türkçe Yama v1.0 (946 MB)](https://github.com/pato384/CrewChief-Turkce-Yama/releases/tag/v1.0)

## Neler var?

**2 şef sesi:** Veyzel ve Levent. İstediğini seçersin.

**2 spotter sesi:** Nazlı ve Begüm.

**Türkçe sesli komutlar:** tetik kelimesi "pato". Aynı soruyu farklı kalıplarla sorabilirsin ("yağ kaç derece", "yağ durumu").

**Türkçe menü yazıları** ve kategorilere ayrılmış komut listesi.

**GERI_AL.bat:** istediğin an her şeyi eski haline getirir.

Pakette Crew Chief'in kendi dosyaları yok. Orijinal programı [thecrewchief.org](https://thecrewchief.org) adresinden indirip kurman gerekiyor.

## Kurulum

**1.** Crew Chief V4 4.19.5.8 sürümünü kurun.

**2.** CrewChief_Turkce_Yama.zip dosyasını bir klasöre çıkarın.

**3.** KUR.bat dosyasını çalıştırın.

**4.** Sesli komut için zip içindeki OKU_BENI.txt dosyasındaki adımları izleyin (iki Microsoft paketi gerekiyor).

## Nasıl yaptık?

Sesleri kayıtla değil, ElevenLabs ile yapay zekâ tarafından ürettik. Şef sesini "çok yapay" bulunca Veyzel'le baştan seslendirdik, spotter için de aynısını yaptık. Cümleleri birebir çevirmedik, anlamından yola çıkıp doğal Türkçeyle yazdık. Tonların tutarlı olması, cümlelerin kesilmemesi ve ses seviyesinin orijinal kliplerle aynı olması için tek tek uğraştık.

Bunun bedeli de oldu: ElevenLabs'te yaklaşık **174 bin kredi** harcandı, **698 bin karakter** ve **15,3 saat** ses üretildi, **42,5 bin** istek yapıldı.

## Güvenlik

Zip 946 MB olduğu için VirusTotal'ın 650 MB sınırına sığmıyor. 4 parçaya bölünüp ayrı ayrı tarandı. Hiçbir parçada tespit yok.

Ana zip SHA256:

`E99E0042519702A05AF38D175A9CA28B6FBAEB78AC2658432E74501AF1506848`

| Parça | SHA256 | VirusTotal |
|---|---|---|
| 1 Betikler ve metinler | `ED0F62733AF20E7EDF648B6B2B37C5F7F92559F4C96C43DC40D53045BF6C95B3` | [0/64](https://www.virustotal.com/gui/file/ed0f62733af20e7edf648b6b2b37c5f7f92559f4c96c43dc40d53045bf6c95b3) |
| 2 Veyzel sesleri | `3935C431CA75DD34073AF3A0C874B838D7C5A8ABDB3EDD2A78D025F816270AAE` | [0/49](https://www.virustotal.com/gui/file/3935c431ca75dd34073af3a0c874b838d7c5a8abdb3edd2a78d025f816270aae) |
| 3 Levent sesleri | `E0473E089974746DA2E14EE9B3852F9621351BF23A5C7458A5EB4DD6E81BF333` | [0/45](https://www.virustotal.com/gui/file/e0473e089974746da2e14ee9b3852f9621351bf23a5c7458a5eb4dd6e81bf333) |
| 4 Spotter ve telsiz | `AAD2AED893F574471CC30D9CD954E0896088E009FFAAFD52876DC76C9055023F` | [0/46](https://www.virustotal.com/gui/file/aad2aed893f574471cc30d9cd954e0896088e009ffaafd52876dc76c9055023f) |

İndirdiğin zip'in SHA256 değerini PowerShell'de `Get-FileHash dosya.zip` ile kontrol edebilirsin, yukarıdakiyle aynı olmalı.

Betik parçasında VirusTotal'ın davranış (Sigma) kuralları uyarı gösterebilir. Bunlar antivirüs tespiti değil, her .bat/.ps1 dosyasında çıkan genel kurallardır. Betiklerin hepsi açık metindir, okuyabilirsiniz.

## Bilinen sınırlar

"Sağ" ve "sol" sesli komutları bazen karışıyor.

Menü yaması yalnızca 4.19.5.8 içindir.

Ralli co-driver sesleri Türkçeleştirilmedi.

Crew Chief güncellenirse menü yazıları İngilizceye dönebilir. Seslerde ya da komutlarda bozulma olursa önce KUR.bat'ı yeniden çalıştırın. Düzelmezse yazın, yeni sürüme uygun bir v1.1 hazırlanacak.

## Kullanım şartları

Sesler yalnızca Crew Chief ile kullanım için paylaşılmıştır. Çıkarılıp başka yerde kullanılamaz, yeniden dağıtılamaz. Tam metin zip içindeki OKU_BENI.txt dosyasındadır. Sesler ElevenLabs ile yapay zekâ tarafından üretilmiştir.
