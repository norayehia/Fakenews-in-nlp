حطclsوsep على عمود sentenيفصل كل جمله عن أخرى
٢ اعمل toknizer بقى لكل جمله يقسمها لكلمات افضل من split 
3 اعمل paddigبحيث لما حدد maxlegnth الجمل يحط باقي اصفار 
٤ عمل I'd بحيت يحط رقم I'd لكل كلمه Feature تتحول لأرقام 
٥ ععمل mask بيحث اكبر صفر تبقيfeature دي مهمه ب١ 
وبعد كده حول داتا لtensor علشان مودل سهل يتعامل معها tensor تمام 
وبعد كده نادي على مودل له شكل معين في pytorch بيحيث dataloador 
وaccuracy لها شكل معين flat accurac
