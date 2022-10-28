# BG-NBD ve Gamma-Gamma ile CLTV Tahmini

## İş Problemi

FLO satış ve pazarlama faaliyetleri için roadmap belirlemek istemektedir. Şirketin orta uzun vadeli plan yapabilmesi için var olan müşterilerin gelecekte şirkete
sağlayacakları potansiyel değerin tahmin edilmesi gerekmektedir.

## Veri Seti Hikayesi: 

Veri seti Flo’dan son alışverişlerini 2020 - 2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan)
olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.

### Değişkenler:

- master_id : Benzersiz müşteri numarası,
- Last_order_channel : Son alışveriş kanalı
- first_order_date : Müşterinin ilk satın alma tarihi
- last_order_date_online : Müşterinin çevrimiçi platformda yaptığı son satın alma tarihi
- last_order_date_offline : Müşterinin çevrimdışı platformda yaptığı son satın alma tarihi
- son alışveriş tarihi last_date_off: Müşterinin çevrimdışı platformundaki son alışveriş tarihi
- order_num_total_ever_offline : Müşterinin çevrimdışı olarak yaptığı toplam satın alma sayısı
- order_num_total_ever_online : Müşterinin çevrimiçi platformunda kullanılabilen satın alma sayısı
- customer_value_total_ever_offline : Müşterinin çevrimiçi alışverişleri için ödediği toplam fiyat
- Interest_in_categories_12 : Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi
