<p align="center">
<a href="https://colab.research.google.com/drive/1uDV3c2GyITQnlPZbmQhAnI9OJeLjU-h6" target="_blank">
 <img src="https://colab.research.google.com/assets/colab-badge.svg" width="110" height="50" border="10" />
</a>
</p>                   

# Olasılık Kütle Fonksiyonu
Olasılık Kütle Fonksiyonu (PMF) ile ilgili Soru ve Çözümü

## Soru: Olasılık Kütle Fonksiyonu
Bir madeni para 4 kez atılıyor. Paranın tura gelmesi durumuna ait olan olasılık kütle fonksiyonunu (kesikli olasılık dağılımını) gösteriniz.

## Çözüm:

Paranın Tura Gelme Durumları:

{YYYY; TYYY,YTYY,YYTY,YYYT; TTYY,TYTY,TYYT,YTTY,YYTT,YTYT; TTTY,TYTT,TTYT,YTTT ;TTTT}

Hiç Tura Gelmemesi:

P(X=0)= 1/2x1/2x1/2x1/2= 1/16

Bir Kere Tura Gelmesi:

P(X=1)= 4x1/2x1/2x1/2x1/2= 4/16

İki Kere Tura Gelmesi:

P(X=2)= 6x1/2x1/2x1/2x1/2= 6/16

Üç Kere Tura Gelmesi:

P(X=3)= 4x1/2x1/2x1/2x1/2= 4/16

Dört Kere Tura Gelmesi:

P(X=4)= 1/2x1/2x1/2x1/2= 1/16

## Açıklama:

Bir rastgele değişkeninin olanaklı değerlerinin sayısı sonlu veya sayılabilir ise X’ e kesikli rastgele değişken denir. X kesikli bir rastgele değişken olduğunda, "fx(X) = P(X=x)" fonksiyonuna rastgele değişkenin olasılık kütle fonksiyonu denir.

Soruda rastgele değişken X olursa, X paranın tura gelmelerinin sayısıdır. Yani X={0,1,2,3,4} olur. Sırasıyla X'in bu değerleri için paranın tura gelme olasılıkları hesaplanır. Hesaplama sırasında 1,2 ve 3 kere tura gelme durumlarında paranın tura gelmesi farklı şekillerde olabileceğinden dolayı tüm tura gelme durumlarının sayısı olasılık değerleri ile çarpılır. Tüm bu hesaplamalardan sonra olasılık kütle fonksiyonu elde edilir.
