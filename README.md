# Derleme yansısı

Bu depo yalnız otomatik iOS derlemeleri için kullanılır. Geliştirme burada yapılmaz.

- Her dalda tek bir commit bulunur; geçmiş tutulmaz, dallar her derlemede baştan yazılır.
- `main` dalında yalnız iş akışı ve bu dosya durur. Derlenecek içerik geçici bir `oyun/<kimlik>` dalına gelir ve
  derleme bitince silinir.
- İş akışı yalnız elle başlatılır (`workflow_dispatch`); bunu yalnız depoya yazma yetkisi olan hesaplar yapabilir.
  `pull_request` tetikleyicisi yoktur.
- Katkı, hata kaydı ve çekme isteği kabul edilmez.

Tüm hakları saklıdır. Buradaki içerik açık kaynak değildir; kopyalanamaz, dağıtılamaz, yeniden kullanılamaz.
