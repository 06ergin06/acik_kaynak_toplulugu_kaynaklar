# Topluluk Kaynaklarına Katkıda Bulunma Rehberi

## İçerik Ekleme Adımları


1. Projeye bir fork atın.
1. İlgili kategori klasörüne giderek yeni `.md` dosyanızı oluşturun veya mevcut bir dosyayı güncelleyin.
2. Değişikliklerinizi commit'leyin (Aşağıdaki commit standartlarına göz atın).
3. `main` dalına bir **Pull Request (PR)** açın.

## Dosya ve İsimlendirme Standartları

Sadece Markdown (.md) dosyaları kabul edilmektedir. İsimlendirme yaparken şu kurallara kesinlikle uyulmalıdır:

* **Sadece küçük harf** kullanın.
* Boşluk yerine **tire (`-`)** kullanın.
* Türkçe karakter (ç, ş, ğ, ü, ö, ı) **kullanmayın**.
* Kısa ve açıklayıcı isimler seçin.

## Markdown İçerik Formatı

1. **Ana Başlık (H1):** Dosyanın en üstünde sadece bir tane `#` ile başlayan ana başlık olmalıdır.
2. **Alt Başlıklar (H2, H3):** Bölümleri ayırmak için `##` ve `###` kullanın.
3. **Bağlantılar (Linkler):** Direkt URL bırakmak yerine, linkleri her zaman isimlendirin.
4. **Kod Blokları:** Eğer notunuzun içinde terminal komutları veya kısa kod örnekleri geçiyorsa, mutlaka backtick (\`\`\`) ile kod bloğu içine alın ve dilini belirtin (örneğin: \`\`\`bash veya \`\`\`c).

## Commit Mesajı Standartları

[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standartlarına uyulmasını tercih ederiz.