الاصدار الاخير يشمل البحث عربي انجليزي 
ومناسب للموبايل 

الداتا موجوده في ملف جيسون تم تحويله من csv الى جيسون باستخدام باور شيل بالاوامر التالية 
Import-Csv .\yourfile.csv |
ConvertTo-Json -Depth 3 |
Out-File -Encoding UTF8 data.json
``
وبعدين حولنا ملف json الى js باضافه سطر في بداية الملف ونهايته كالتالي 

const data = 
//json file here 
;
