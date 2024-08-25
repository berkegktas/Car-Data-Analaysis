# Car-Data-Analaysis
Bazı temel analiz fonksiyonları pratik etmek amaçlı oluşturduğum bir repodur.Umarım faydalanırsınız.! :)
# Hangi Fonksiyonları kullandık.

	• pd.read_csv -- csv dosyamızı okur.
	• copy() -- veri setimizi kopyalar.(yeni bir değişkene atarken kullanılabilir)
	• head() - Verisetininden ilk n satırı okur, getirir 
	•  tail() - Verisetininden son n satırı okur, getirir (by default, n=5)
	• shape - Verisetimizin kolon(sütun) ve satır sayısını getirir, yapısını-şeklini verir
	• df.index - Verisetimizin kaç adet indexi olduğunu verir, kaçtan başlamış kaçta bitmiş onu verir
	• df.columns - Kolonları getirir
	• df.size - Verisetindeki toplam kaç adet hücre(element vb.) varsa getirir
	• df.describe() - Verisetimiz hakkında bazı işlemleri yapmış bir şekilde verir (mean,min,max,std vb.)
	• df.dtypes - Verisetimizin kolon tiplerini verir
	• df.info() - Birçok bilgi verir veriseti hakkında
	• df.unique() - Her sütunda eşsiz olan kaç veri var onları getirir
	• df.nunique() - Her sütunda eşsiz olan kaç veri var adedini getirir NaN değerleri saymaz
	•  df.isnull().values.any() - Verisetinde eksik veri var mı yok mu diye sorar ve boolean dönderir
	• df.isnull().sum() - Her kolonda eksik veri var mı varsa kaç adet onu getirir
	• df.isnull().sum().sum() - Verisetindeki toplam eksik değer sayısını verir
	• count() - Her kolonun(sütunun) dolu olan hücrelerini sayar sütün-sütun veri verir,ancaaak eksik veri(NaN,null) olanları saymaz
	• value_count() - Her kolonda olan farklı verilerin sayı adedini verir
