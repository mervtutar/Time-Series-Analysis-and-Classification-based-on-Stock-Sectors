# Time Series Analysis and Classification based on Stock Sectors
 Yapay Zeka Uzmanlık Programı-Tübitak Veri Yogun Uygulamalar Modül Projesi
Milli Teknoloji Hamlesi altinda Yapay Zeka Uzmanlık Programı kapsamında Tübitak tarafından verilen 18 saatlik Veri Yogun
Uygulamar egitimi sonunda bu proje tamamlanmıştır.
Bu proje icerisinde amac farkli sektorlerden elde edilmis zaman serileri uzerinden elde edilen faktorler
uzerine kurulmus bir classification modeli kurarak benzerlik calismasi yapmaktir.

Bu proje, asagidaki surecleri kapsayacak:

• Sektorlerin listesine bir **web-scraping** ile erisilmesi ve verilerin elde edilmesi (yfinance,
investpy, quandl)

• 2005-01-01 yilindan itibaren aylik getirelerden olusan serilerin elde edilmesi

• 3 buyuk sektor uzerinden getirilerin faktorleri(momentum gibi) hesaplanmasi

• Bu momentum serileri uzerinden bir tsfresh ile feature engineering yapilmasi (imputing, encoding,
transformation, ve daha fazlasi)

• Yeni elde edilmis feature ve sektor siniflari uzerinden bir model kurulmasi (en iyi model
secmesi)

• Diger sektorlerden ornekler alip ayni feature engine yontemleri yaptik sonra hangi sektore
benzedigine karar vermek.

• Bonus Mesela Real-Estate sektorunde bulunan butun sembollerin tahmini edildikten sonra
cogunluk hangi sektore(T,F,H) benzedigi bilgisine erismek.
