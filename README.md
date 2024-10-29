# AutomationExercise.com Ürün Doğrulama Test Otomasyonu

## Genel Bakış

Bu repo, **AutomationExercise.com** üzerindeki ürün gezintisini ve ürün detaylarını doğrulamak için Java, Selenium WebDriver ve JUnit kullanılarak yazılmış otomatik bir test senaryosu içermektedir. Bu test, kullanıcıların "Tüm Ürünler" sayfasına gidip ürün listesini görebildiğini ve ilk ürünün detaylarına başarılı bir şekilde erişebildiğini doğrulamayı amaçlar.

## Test Senaryosu

Test aşağıdaki adımları kapsamaktadır:

1. **AutomationExercise Web Sitesini Başlatma**: 
   - Web sitesini açar ve ana sayfadaki logonun görüntülendiğini doğrulayarak sayfanın doğru yüklendiğinden emin olur.
  
2. **Ürünler Sayfasına Gitme**: 
   - "Products" (Ürünler) bağlantısına tıklayarak tüm ürünlerin listelendiği sayfaya geçiş yapar.
  
3. **Tüm Ürünlerin Görüntülendiğini Doğrulama**: 
   - "All Products" başlığının görüntülendiğini doğrular ve mevcut URL'nin beklenen URL ile eşleştiğini kontrol eder.
