# Git Versiyon Kontrolü ve Log Takibi

Bu hafta Git komutları üzerinde pratikler yaparak versiyon kontrol sisteminin temel mantığını kavradım. Dosyalar üzerinde yaptığım değişiklikleri adım adım nasıl kaydedeceğimi ve geçmişe nasıl döneceğimi deneyimledim. 

Uyguladığım temel komutlar ve çalışma akışım şu şekildeydi:
* **`git add .`**: Proje klasörümde oluşturduğum veya üzerinde değişiklik yaptığım tüm dosyaları tek seferde "Staging Area"ya (hazırlık aşamasına) almayı öğrendim.
* **`git commit -m "..."`**: Hazırlık aşamasına aldığım bu dosyaları, yaptığım işi anlatan açıklayıcı bir mesajla paketleyip (commit) yerel (local) ortamıma kesin olarak kaydettim.
* **`git log`**: Yaptığım tüm kayıt işlemlerinin geçmişine dönüp bakmak için log kayıtlarını inceledim.

Bu döngüyü daha iyi anlamak için pratik bir senaryo uyguladım: Klasörün içinden bilinçli olarak bir dosyayı sildim. Ardından tekrar `git add .` komutu ile bu silme işlemini Staging Area'ya aldım ve yeni bir commit atarak kaydettim. Son olarak `git log` komutunu çalıştırarak adım adım ne yaptığımı, eski paketleri (commitleri) ve dosyanın silindiği anı terminal üzerinden detaylıca gözlemledim.
Ek olarak terminalden aldığım kod görüntülerini paylaştım. 
![Terminal Görüntüsü 1](images/image2.png)