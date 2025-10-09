Notification Kuralı  
        status == true olmalı.
        testMode ayarı: bildirimin testMode==true ise, script’teki testMode da true değilse atlanır.
        Versiyon: Bildirimin version’ı, Application.version’dan küçükse atlanır (yani >= olmalı).
        id kontrolü: id > 0 olmalı ve PlayerPrefs’te kayıtlı notificationID’den büyük olmalı (yeni olmalı).
        İlk uygun bildirim bulununca döngü kırılır.