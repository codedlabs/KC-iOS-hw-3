  <h1 align="right">الواجب 3 </h1>

<p dir="rtl">
<img src="/hw3-1.gif" width="200" alt="alt_text" title="image_tooltip">
</p>


<br>


---


<p dir="rtl">
نبذة عن الواجب</p>


<p dir="rtl">
في هذا التطبيق يجب إدخال المصروفات وعرضها كما هو موضح بالصور.</p>



---

<p dir="rtl">
شرح الواجب </p>



<p dir="rtl">
1. إضافة هيكل struct باسم Expenses وتعريف المتغيرات كالآتي :

<p dir="rtl">
var store : String   -> اسم المحل

<p dir="rtl">
var paid : Double   -> القيمة المدفوعة

<p dir="rtl">
var profileImage : String   -> صورة المحل

<p dir="rtl">
var purchases : String      ->    اسم المشتريات


<p dir="rtl">
2. عمل متغير من نوع مصفوفة الكائنات وإضافة العناصر إليها.

<p dir="rtl">
var expensesArray = [Expenses(store: "..",  paid: ..,  profileImage: "..",  purchases: "..")]

<p dir="rtl">
4. عمل List لتعرض عرض عناصر مصفوفة الكائنات كما هو موضح بالصورة . مثال :

List(expensesArray){ oneExp in

           

   }

<p dir="rtl">
* ملاحظة : يمكنك عمل scroll view و ForEach بدلاً عن List


---

<p dir="rtl">
شرح البونس</p>


<p dir="rtl">
1.  إضافة مصفوفة من النصوص بدلاً عن نص واحد في خانة المشتريات في الهيكل . كالتالي :

<p dir="rtl">
var purchases : String   ->  var purchases : [String]

 
<p dir="rtl">
2. إضافة Slider كما هو موضح بالصورة ، عند تحريكه يقوم بعمل شفافية للون الخلفية .


.opacity( )   -> شفافية للون



<p dir="rtl">
<img src="/hw3-2.gif" width="200" alt="alt_text" title="image_tooltip">
</p>
