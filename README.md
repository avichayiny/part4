ברפוסיטורי זה מצורפים דפי wiki כדלהלן: part4/wiki_pages לפי הנושאים שהוגדרו.
בדפי הwiki כל אחד לפי הנושא שלו מובאות דוגמאות ההרצה שנתבקשו בעזרת צילומי מסך מהאפליקציה ומהאתר.
כמו כן ברפוסיטורי זה נמצאים שרת הcpp שהתבקשנו לבנות בתרגיל זה שנקרא UpdateServer.cpp וכן קבצי ה web client.
קבצי הandroid client ושרת הnode js נמצאים בrepositories ייעודיים שהוגשו בקובץ הdetails באתר המודל.

ברפוסיטורי של האנדרואיד שמוגש בקובץ הdetails יש לקחת את הקבצים מענף שנקרא part4.
ברפוסיטורי של השרת של ה node js שמוגש בקובץ הdetails יש לקחת את הקבצים מענף שנקרא node-js-server-part-4.


הוראות הרצה:
יש להריץ תחילה את שרת הcpp בעזרת פקודת קימפול של g++: g++ -o UpdateServer UpdateServer.cpp -pthread. ואז להריץ בעזרת פקודת ./UpdateServer. שורת הקימפול וההרצה מוצגת בתיקיית הwiki הייעודית.
נדרש להגדיר דאטה בייס בmongoDB ולקרוא לו youTube. הדאטה בייס צריך להכיל שני אוספים: users וvideo.
את users יש להשאיר ריק.
לאוסף video יש לטעון את הקובץ VideoList.json שנמצא בתיקיית server-side או מהבראנצ הראשי של ריפו זה.
לאחר מכן יש להריץ את השרת. להיכנס לתיקיית server-side ולהריץ את השרת בעזרת פקודת npm start.
ניתן לשנות את הport שעליו רץ השרת ע"י שינוי המשתנה PORT בתיקיית config בקבצים env, env.local, env.test.
בקבצים אלו יש להגדיר את הlocalhost של הmongoDB ואת שם הdatabase (youTube). שם הדאטה בייס מוגדר להיות youTube באופן דיפולטיבי. וגם הlocalhost מוגדר דיפולטיבית שם.
באופן דיפולטיבי השרת רץ על port 90.
לאחר מכן יש להריץ את שרת הnode js שאותו יש לקחת מהרפוסיטורי המצורף בקובץ הdetails ע"י מעבר לתיקייה server-side בעזרת פקודת cd. ולאחר מכן פקודת npm start.
לאחר שהשרתים רצים ניתן להיכנס לאתר ע"י כתובת localhost:90. וכן להריץ את האנדרואיד סטודיו מהרפוסיטורי המיועד בקובץ הdetails.

ניתן להיעזר בשביל ההרצה בדפי הwiki של הרמת הסביבה וכן בהוראות הנמצאות בבראנצ part-2 בריפוסיטורי של האנרואיד שהוגש בקובץ הdetails של ריפו זה.




