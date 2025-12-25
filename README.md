Bu çalışmamın amacı, derin öğrenme tekniklerini kullanarak göğüs röntgeni görüntüleri üzerinden Pnömoni ve Normal ayrımını otomatik, hızlı ve yüksek doğrulukla yapabilen bir karar destek sistemi geliştirmektir. 
Çalışma kapsamında Baseline CNN, Transfer Öğrenme tabanlı ResNet50 ve Vision Transformer (ViT) mimarileri karşılaştırmalı olarak analiz edilmiştir. 
Hugging Face "AiresPucrs/chest-xray" veri seti üzerinde gerçekleştirilen deneylerde, modellerin performansı %80/20 eğitim-test ayrımı ile değerlendirilmiştir. 
Ayrıca, modellerin karar mekanizmaları Grad-CAM tekniği ile görselleştirilerek, akciğerdeki patolojik infiltrasyonlara doğru bir şekilde açıklanabilirliği gösterilmiştir.
