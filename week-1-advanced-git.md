# İleri Seviye Git Komutları ve Branch Yönetimi

Bugün Git versiyon kontrol sisteminin daha derinlerine inerek ileri seviye komutların eğitimlerini tamamladım ve her birini terminal ile GitHub üzerinde aktif olarak pratik ettim.

## 1. Dosya Yönetimi ve Değişiklik Takibi
* **`git diff`**: Dosyalarda yaptığım değişiklikleri henüz commit etmeden önce satır satır karşılaştırmayı ve incelemeyi öğrendim.
* **`git reset HEAD <dosya>`**: Staging Area'ya (hazırlık aşamasına) yanlışlıkla eklediğim bir dosyayı (örneğin `deneme4.txt`) geri çıkarmayı test ettim.
* **`git checkout`**: Yaptığım değişiklikleri iptal edip, dosyanın son commit edilmiş tertemiz haline geri dönmeyi denedim.
* **`git rm` ve `git rm -r test/`**: Tekil dosyaları ve klasörleri (`test/` gibi) Git üzerinden kalıcı olarak silme işlemlerini uyguladım.
* **`git mv deneme.txt test.txt`**: Dosyaları taşımak veya isimlerini değiştirmek (rename) için Git Move komutunu kullandım.

## 2. Branch (Dallanma) Mantığı ve Stash
* **`dev` ve `master/main` Branch Farkı**: Gerçek projelerde `master` (veya `main`) dalının canlıdaki hatasız çalışan kod olduğunu; `dev` (development) dalının ise geliştirme ve test aşamasındaki kodları tuttuğunu kavradım.
* **`git branch`**: Projemde yeni dallar (branch) oluşturmayı ve bu dallar arasında geçiş yaparak birbirlerini etkilemeden kod yazmayı pratik ettim.
* **`git stash`**: Üzerinde çalıştığım ama henüz commit edecek kadar bitirmediğim kodları geçici olarak hafızaya (rafa) kaldırmayı ve farklı bir işi hallettikten sonra geri getirmeyi öğrendim.

## 3. Uzak Sunucu (Remote) ve Diğer Araçlar
* **`git fetch` ve `git pull`**: Uzak sunucudaki (GitHub) değişiklikleri local'ime yansıtmadan sadece kontrol etmek için `fetch`, değişiklikleri çekip kendi kodumla birleştirmek için `pull` komutlarını uyguladım.
* **`git push`**: Local ortamımda hazırladığım commit'leri GitHub'a gönderme işlemini pekiştirdim.
* **Git Alias**: Sık kullandığım uzun Git komutlarına kendi belirlediğim kısa isimleri (kısayol) atayarak terminalde hız kazanmayı öğrendim.
* **`.gitignore` Kullanımı**: Projemde GitHub'a gitmesini istemediğim özel veya gereksiz dosyaları `.gitignore` dosyası yaratarak nasıl gizleyeceğimi test ettim.
* **README Kavramı**: Bir projenin vitrini olan README dosyasının önemini, projeyi ziyaret eden diğer geliştiricilere projenin amacını ve kurulumunu anlatan temel rehber olduğunu detaylıca inceledim.