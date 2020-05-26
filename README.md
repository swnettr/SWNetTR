# SWNetTR++
# TÜRKÇE DUYGU SÖZLÜĞÜ
# TURKISH SENTIMENT LEXICON

****************************************************************************************************************************
Sayın Araştırmacı;

Bu Türkçe Duygu Sözlüğü, doktora tezi çalışması kapsamında geliştirilmiş olup,
kullanılması ve dağıtılması tamamen serbesttir. Amacımız dilimizde yapılacak
çalışmalara kaynak oluşturabilmektedir. 

Akademik amaçlı kullanımınızda, aşağıdaki yayınlara çalışmalarınızda referans vermenizi rica ederiz.

İyi çalışmalar....


REFERANS VERİLECEK YAYINLAR:
---------------------------
1) F. Sağlam, B. Genç, H. Sever, "Extending a Sentiment Lexicon with Synonym-Antonym Datasets: SWNetTR++", 
   Turkish Journal of Electrical Engineering and Computer Sciences, 27 (2019) 1806-1820. 
   
2) F. Sağlam, B. Genç, H. Sever, "Developing Turkish Sentiment Lexicon for Sentiment Analysis Using Online News Media", 
   IEEE/ACS 13th International Conference of Computer Systems and Applications (AICCSA), 
   Nov 29 – Dec 02 2016, Agadir, Morocco, 2016.   


SÖZLÜĞÜN TÜM GELİŞTİRİLME YÖNTEM VE SÜREÇLERİ HAKKINDA BÜTÜN BİLGİLER İÇİN:
--------------------------------------------------------------------------
   YÖK Tez Merkezi, 10253867 referans numaralı, 
   "Otomatik Duygu Sözlüğü Geliştirilmesi ve Haberlerin Duygu Analizi" konulu doktora tezi.


TÜRKÇE KARAKTERLERDEN DOLAYI ENCODING PROBLEMI YAŞAYANLAR İÇİN PYTHON KOD SATIRI:
--------------------------------------------------------------------------------
   import pandas as pd <br>
   SWNetTR = pd.read_csv(r"...\YOUR_PATH\SWNetTR++.csv", sep=';', decimal=",", encoding="utf-8-sig")



Fatih SAĞLAM
fsaglam2002@yahoo.com

****************************************************************************************************************************
