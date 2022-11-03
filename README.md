1. Kurulan programın Dll klasörü içindeki SolutionAccounting ile başlayan 6 adet .dll dosyası kendi projenizin exe dosyasının bulunduğu klasöre veya dll dosyalarınızın bulunduğu klasöre kopyalanır.
2. Kopyalanan dosyalarda SolutionAccounting.Import.dll isimli dosya projenize referans olarak eklenir.
3. Projenizin App.config dosyası içindeki connectionStrings bölümüne AccountingContext isminde bir connection eklenerek server ayarlarınıza göre doldurulur.
4. Form1.cs içindeki kodlar referans alınarak gerekli kodlar projenize eklenir.
