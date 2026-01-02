Bu çalışmamın amacı, derin öğrenme tekniklerini kullanarak göğüs röntgeni görüntüleri üzerinden Pnömoni ve Normal ayrımını otomatik, hızlı ve yüksek doğrulukla yapabilen bir karar destek sistemi geliştirmektir. 
Çalışma kapsamında Baseline CNN, Transfer Öğrenme tabanlı ResNet50 ve Vision Transformer (ViT) mimarileri karşılaştırmalı olarak analiz edilmiştir. 
Hugging Face "AiresPucrs/chest-xray" veri seti üzerinde gerçekleştirilen deneylerde, modellerin performansı %80/20 eğitim-test ayrımı ile değerlendirilmiştir. 
Ayrıca, modellerin karar mekanizmaları Grad-CAM tekniği ile görselleştirilerek, akciğerdeki patolojik infiltrasyonlara doğru bir şekilde açıklanabilirliği gösterilmiştir.

Çalışma Google Colab üzerinde çalıştırılmıştır. Ayrıca drive üzerinde model eğitimleri kaydedilmiştir. Her model için farklı veri setleri üzerinde doğrulama çalışması yapılmış ve model başarıları gösterilmiştir. 
Eğitilmşiş modellere https://www.dropbox.com/scl/fo/0wiu5w9jk9qkjvid5ju7l/AHCH02-w6buIlkU-UCv2-YY?rlkey=m6r61mjw9fdeuadeyr6ju8oxa&st=69adf26v&dl=0 adresindne eişilebilir. Colab da üzerinde uygun dosya yapısı uyarlanarak doğrulama testleri yapılabilir.
