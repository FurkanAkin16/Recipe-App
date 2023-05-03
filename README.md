# Recipe-App


-----------------------
Bu projenin amacı, kullanıcıların tarif arşivlerinde arama yapabilmesi ve buldukları tarifleri kaydedebilmesi için bir web uygulaması oluşturmaktır. Uygulamada, kullanıcının arama yapabileceği bir arama çubuğu bulunur ve searchRecipes() fonksiyonu kullanılarak kullanıcının girdiği anahtar kelimeye göre tarifler aranır. Bu fonksiyon, tarifleri getirmek için fetchRecipes() fonksiyonunu kullanır ve sonuçları ekranda göstermek için displayRecipes() fonksiyonunu kullanır.

Kullanıcılar, seçtikleri tarife tıkladıklarında, tarifin ayrıntılarını gösteren bir sayfaya yönlendirilirler. Bu ayrıntıları getirmek için getRecipeDetails() fonksiyonu kullanılır ve sonuçları göstermek için displayRecipeDetails() fonksiyonu kullanılır.

Kullanıcılar, beğendikleri tarifleri kaydetmek için saveRecipe() fonksiyonunu kullanabilirler. Kaydedilen tarifleri görmek için getBookmarks() ve displayBookmarks() fonksiyonları kullanılabilir. Kullanıcılar, daha önce kaydedilmiş bir tarifi silmek istediklerinde deleteRecipe() fonksiyonunu kullanabilir veya tüm kaydedilmiş tarifleri silmek için clearBookmarks() fonksiyonunu kullanabilirler.

Bu proje, JavaScript kullanarak kullanıcılara tarifleri arama, seçilen tarifleri ayrıntılı olarak görme ve beğendikleri tarifleri kaydetme gibi olanaklar sunar.

----------------------------------------------------------------------------------------------------
fetchRecipes() fonksiyonu: Bu fonksiyon, Spoonacular API'si üzerinden tarifleri çekmek için kullanılan fetch() yöntemini kullanır.

searchRecipes() fonksiyonu: Bu fonksiyon, kullanıcının girdiği anahtar kelimeye göre tarifleri aramak için kullanılır. Bu fonksiyon, fetchRecipes() fonksiyonunu kullanır.

displayRecipes() fonksiyonu: Bu fonksiyon, tarifleri ekrana görüntülemek için kullanılır. Tariflerin adı, resmi ve özeti bu fonksiyon tarafından oluşturulur.

getRecipeDetails() fonksiyonu: Bu fonksiyon, kullanıcının seçtiği bir tarifi ayrıntılarıyla göstermek için kullanılır. Bu fonksiyon, fetchRecipes() fonksiyonunu kullanır.

displayRecipeDetails() fonksiyonu: Bu fonksiyon, seçilen tarifin ayrıntılarını ekrana görüntülemek için kullanılır.

saveRecipe() fonksiyonu: Bu fonksiyon, kullanıcının seçtiği bir tarifi yer imlerine eklemek için kullanılır. Tarif, yer imleri listesine eklenir ve daha sonra yer imleri sayfasında görüntülenebilir.

deleteRecipe() fonksiyonu: Bu fonksiyon, kullanıcının yer imleri listesindeki bir tarifi silmek için kullanılır. Tarif, yer imleri listesinden kaldırılır ve daha sonra yeniden görüntülenemez.

getBookmarks() fonksiyonu: Bu fonksiyon, yer imleri listesindeki tüm tarifleri getirmek için kullanılır.

displayBookmarks() fonksiyonu: Bu fonksiyon, yer imleri listesindeki tüm tarifleri ekrana görüntülemek için kullanılır.

clearBookmarks() fonksiyonu: Bu fonksiyon, yer imleri listesindeki tüm tarifleri silmek için kullanılır.
