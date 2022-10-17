# Git_Docs
# Git 


- هو برنامج لادارة النسخ او قاعدة بيانات لتخزين العمليات والتحديثات التي  قمت باجرائها على الملف او المشروع، وايضا يمكنني الرجوع الى تلك التعديلات اي وقت ويظهر اسم الجهاز   وتاريخ التعديل.  

  بانشاء مجلد مخفي لكي يقوم بتتبع ومراقبة الملف او المشروع . Git يقوم -

  
 . (Commit) عملية الحفظ تسمى اسم اللقطه  - 
 

. (repository) يتم حفظ وتخزين الملفات فيما يسمى  مستودع  -



<img width="1159" alt="image" src="https://user-images.githubusercontent.com/91524880/196148922-c88d203c-1e3a-457b-bada-55933bcb15ba.png">



# انشاء مستودع جديد

-    لكي انشاء مستودع  استخدم امر -------------- git init 

  في هذا الوقت عند كتابة الامر يصبح للمشروع قاعدة بيانات جاهزه لتخزين والتقاط التعديلات تخزينها.

     
     ملاحظه :

           git init ١- يتم انشاء مستودع في المشروع مرا واحده اي استخدم الامر   .

          ٢-في هذا الامر فقط انشاء قاعده بيانات  فارغه لا يقوم بتخزين او تعديلات موجوده في مشروعك
          
          
        
        -   استخدم امر لتتبع ملف    ----------------<git add <name_file   او   <. > git add                     
          
          
          ملاحظة:
          
                                                                                                                                      ١- يمكن في هذه الحاله اضيف كذا ملف في حالة stage وثم رفعه في كومت واحد.

                                                                                                                                     ٢- يمكن التراجع عن هذا الحاله . 

-   استخدم امر للحفظ الملف     ----------------------"git commit -m "massage
                                                                                                                                         ملا حظة :
                                                                                                                                        ١-يمكن من خلال هذا اسم هذا الكومت الرجوع الى النسخ .

                                                                                                                                        ٢- لايمكن التراجع عن حفظ الملف في هذا الامر. 


# نسخ مستودع موجود مسبق 


- استخدم امر لاستنساخ مستودع موجود في GitHub. -------------------ا  <كود  >git clone 
 
                                                                                   :   ملاحظة
git init في هذه الحالة ماستخدم امر 























The "merge" command is used to integrate changes from another branch.

To do a merge (locally), git checkout the branch you want to merge INTO. Then type git merge <branch> 
where <branch> is the branch you want to merge FROM.

طريقة الدمج
// git merge (اسم البرانش)

Type of merge 

1- Fast forward merge (كل البرانشات تكون على امتداد واحد)
Fast forward merge can be performed when there is a direct linear path from the source branch to the target branch. In fast-forward merge, git simply moves the source branch pointer to the target branch pointer without creating an extra merge commit.

2- Three-way merge (امتداد البرانشات يكون مختلف)
 A three-way merge is performed after an automated difference analysis between a file "A" and a file "B" while also considering the origin, or common ancestor, of both files “C"


<img width="956" alt="image" src="https://user-images.githubusercontent.com/91421012/196152755-c4a02609-e886-43e1-8a14-92ccac8cbfac.png">

 A three-way merge is performed after an automated difference analysis between a file "A" and a file "B" while also considering the origin, or common ancestor, of both files “C"
