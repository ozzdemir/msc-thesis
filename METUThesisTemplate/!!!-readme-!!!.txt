Latex sablonunda jüri üyesi sayisini degistirmek için asagidaki adimlari uygulayin.

Latex sablonu default olarak bes jüri üyelidir.  Üç jüri üyesine dönüstürmek için;
	1.thesis.text doyasinda  \documentclass komut satirini asagidaki gibi degistirin;
		\documentclass[chaparabic,ceng,ms,12pt,oneandhalf,threejury]{metu}
	
	2.Dört ve besinci jüri üyelerinin bilgilerinin yer aldigi komut satirinin basina % isareti ekleyerek komut satirini açiklama satirina dönüstürün.

Bes Jüri üyesine dönüstürmek için;
	1.thesis.text doyasinda  \documentclass komut satirini asagidaki gibi degistirin;
		\documentclass[chaparabic,ceng,ms,12pt,oneandhalf,fivejury]{metu}
	2.Dört ve besinci jüri üyelerinin bilgilerinin yer aldigi komut satirinin aktif oldugundan emin olun.


-------------------------------------------------------------------------------
Latex sablonunda imza sayfasina jüri tarihimi nasil yazabilirim?
	metu.cls dosyasinda Datelabel kismina (örn: \@datelabel: \@26.03.2020) jüri tarihinizi yazmalisiniz.


-------------------------------------------------------------------------------


Bu sablon ile olusturdugunuz tez taslaklarinizin en basina "Tez Sablonu Onay Formu.docx" belgesini imzalayarak eklemeniz gerekmektedir.

-------------------------------------------------------------------------------

You have to sign and add the "Tez Þablonu Onay Formu.docx" document at the beginning of your thesis drafts.