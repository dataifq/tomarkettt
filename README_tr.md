
## TomarketBot  
| Desteklenen Özellikler | Durum |
|------------------------|:------:|
| Otomatik Talep Etme     |   ✅   |
| Otomatik Oyun Oynama    |   ✅   |
| Çoklu Hesap Desteği     |   ✅   |
| Proxy Desteği           |   ✅   |

## Uyarı!
[Telegram Kullanım Koşulları](https://core.telegram.org/api/obtaining_api_id#using-the-api-id) gereğince, resmi olmayan Telegram API istemcilerini kullanarak kayıt olan ya da giriş yapan tüm hesaplar, Hizmet Koşulları ihlallerini önlemek için gözlem altına alınır.

Bu yüzden dikkatli olun, umarım hesabınız yasaklanmaz.

## Ayarlar Veri Dosyası
| Ayar                     | Açıklama                                                                 |
|--------------------------|-------------------------------------------------------------------------|
| query_id | `data.txt` dosyasını verilerinizle doldurun. Verileri nasıl alacağınızı öğrenmek için (#[Verileri Nasıl Alırsınız](#how-to-get-app-webdata-telegram)) bölümüne başvurabilirsiniz. |

## Gereksinimler
- Python 3.9 (buradan indirebilirsiniz: [link](https://www.python.org/downloads/release/python-390/))
- Verileri Nasıl Alırsınız (README.md dosyasının alt kısmında bulabilirsiniz)

Python ve Git'in bilgisayarınızda kurulu olduğundan emin olun.

## Öneri: Python 3.8+ (3.8 ve üzeri veya en son sürüm) kullanın

Python sitesi: [burada](https://python.org)  
Git sitesi: [burada](https://git-scm.com/)

## Bu depoyu klonlayın

```
git clone https://github.com/kucingeros/tomarkettt
```

## Tomarket dizinine gidin

```
cd tomarkettt
```

## Gerekli kütüphaneyi kurun

```
python -m pip install -r requirements.txt
```

## `data.txt` dosyasını düzenleyin, token bilgilerinizi `data.txt` dosyasına girin. Hesap tokeninizi nasıl bulacağınızı öğrenmek için "Hesap Tokeni Nasıl Bulunur" bölümüne bakın. Bir satır bir hesap verisine karşılık gelir. İkinci bir hesap eklemek istiyorsanız, yeni bir satır ekleyin!

## Ana programı çalıştırın

```
python bot.py
```

## Telegram Web Verileri Nasıl Alınır
- Mini uygulamanın üzerine sağ tıklayın > f12 veya incele öğesini seçin
- Konsola gidin > "allow pasting" yazın
- Kopyala yapıştır > 
- `Telegram.WebApp.initData` komutunu kopyalayın

*Not: `data.txt` dosyasını query_id=xxx ile doldurun
