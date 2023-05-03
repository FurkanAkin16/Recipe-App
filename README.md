# Recipe-App

Youtube Link: https://youtu.be/tONOj4XrF70

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

-----------------------

Eng


The purpose of this project is to create a web application that allows users to search through recipe archives and save recipes they find. The application includes a search bar where users can enter keywords to search for recipes. The searchRecipes() function is used to search for recipes based on the keywords entered by the user. This function uses the fetchRecipes() function to retrieve the recipes and the displayRecipes() function to display the results on the screen.

When users click on a recipe, they are directed to a page that displays the details of that recipe. The getRecipeDetails() function is used to retrieve the recipe details, and the displayRecipeDetails() function is used to display the results on the screen.

Users can save recipes they like using the saveRecipe() function. The getBookmarks() and displayBookmarks() functions can be used to view the saved recipes. If users want to delete a previously saved recipe, they can use the deleteRecipe() function. Alternatively, they can use the clearBookmarks() function to delete all saved recipes.

This project uses JavaScript to provide users with features such as recipe search, detailed recipe viewing, and recipe bookmarking.

fetchRecipes() function: This function uses the fetch() method to retrieve recipes from the Spoonacular API.

searchRecipes() function: This function is used to search for recipes based on the keywords entered by the user. It uses the fetchRecipes() function.

displayRecipes() function: This function is used to display the recipes on the screen. The name, image, and summary of each recipe are created by this function.

getRecipeDetails() function: This function is used to retrieve the details of a selected recipe. It uses the fetchRecipes() function.

displayRecipeDetails() function: This function is used to display the details of a selected recipe on the screen.

saveRecipe() function: This function is used to add a selected recipe to bookmarks. The recipe is added to the bookmarks list and can be viewed later on the bookmarks page.

deleteRecipe() function: This function is used to delete a recipe from the bookmarks list.

getBookmarks() function: This function is used to retrieve all recipes from the bookmarks list.

displayBookmarks() function: This function is used to display all recipes from the bookmarks list on the screen.

clearBookmarks() function: This function is used to delete all recipes from the bookmarks list.
