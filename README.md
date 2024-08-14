## CycleGAN NEDİR?


CycleGAN, iki farklı domain (örneğin at ve zebra resimleri) arasında görüntü dönüşümü yapan bir yapay zeka modelidir. Model, her iki domain için birer generatör ve ayırt edici içerir. Generatörler, bir domain'deki görüntüleri diğerine dönüştürürken, ayırt ediciler bu görüntülerin gerçek mi yoksa üretilmiş mi olduğunu ayırt eder.

CycleGAN, döngü tutarlılığı (cycle-consistency) kullanarak, bir görüntüyü önce diğer domain'e, sonra tekrar orijinal haline dönüştürdüğünde, başlangıçtaki haliyle tutarlı olmasını sağlar. Bu sayede, at resimlerinden zebra resimlerine ya da gündüz fotoğraflarından gece fotoğraflarına dönüşüm gibi işlemler gerçekleştirilebilir.
