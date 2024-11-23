# Preprocessing_missData
‏عملت preprocessing ل داتا ست بسيطة customer lifetime
‏اشتغلت على ال داتا  المفقودة، حبيت اعمل مقارنة بواسطة موديل بين انه احذفها أو استبدلها

‏رحت عملت مقارنة
2-drop null data
حذفت كل ال observations اللي معاها داتا مفقودة
2-mean/median/mode imputation 
‏في الحتة دي استبدلت أداة المفقودة ب ال mean
3-multiple imputation using regression
لازم يكون عندك معرفة ML لاستخدام لاستبدال حسب النمط 
4-nearest neighbour imputation 
‏ وهنا أن هنستبدل الداتا على حسب الدتا المتشابهة

‏رحت عملت له مقارنة على حسب
‏ mean absolute error
