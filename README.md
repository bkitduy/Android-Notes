# Android-Notes
1.	Android
  - Native : Java (Android Studio, Eclipse)-OOP , Kotlin (Android Studio, Intellij IDE)- OOP and Structure, Scala (Intellij IDE)-OOP and Structure
2.	Database local:
  -  SQLite (SQL):
	  + Can use some framework ORM (Sugar ORM?) to convert data from database to object model in OOP
  - Realm (SQL):
	  + https://realm.io/docs/java/latest/
  - SQLighter (SQL):
	  + https://github.com/vals-productions/sqlighter
  - Couchbase Lite (NoSQL)

3.	Other Libraries:
  - GSON : Parse JSON- https://github.com/google/gson
  - Hackson-databind: https://github.com/FasterXML/jackson-databind
  - Otto: http://square.github.io/otto/
  - Parceler (base on Parcelable): https://github.com/johncarl81/parceler
  - Retrofit/Volley : Network calls
    http://laptrinhandroid.xyz/2015/09/16/gioi-thieu-retrofit-2-0-a-type-safe-http-client-for-android/
  - Robolectric
  - Rx Java
  
  3.1	Design Pattern:
    - Creational Pattern (Khởi tạo object): Builder, Abtract Factory, Factory Method, Singleton, Prototype
    - Structural Pattern (Thiết lập, định nghĩa quan hệ giữa các object): Adapter, Bridge, Composite, Decorator, Façade, Proxy, Flyweight
    - Bahavioral Pattern (Dùng trong thực hiện các hành vi của object): Interpretor, Iterator, Observer,Template Method, Chain of Responsibility, Command, Mediator, Memento, State, Startegy and Visitor
    - References:
    	+ http://laptrinh.vn/d/4346-design-pattern-la-gi-huong-dan-design-pattern.html
    
  3.2	Notes:
    - Save States Fragment/Activity: http://inthecheesefactory.com/blog/fragment-state-saving-best-practices/en
    - Style writing: http://www.google.com/design/spec/style/writing.html#writing-capitalization-punctuation

  3.3	Awesome libraries
    - UX/UI: https://github.com/wasabeef/awesome-android-ui
    - Libraries: https://github.com/wasabeef/awesome-android-libraries
    
  3.4   Some explains:
    - Fragment: 
    	+ A Fragment must always be embedded in an Activity
    	+ Use android.app.Fragment with Activity
    	
    - FragmentActivity:
    	+ Use the FragmentActivity to hold your Fragments
    	+ Use android.support.v4.app.Fragment with FragmentActivity
    	
    Don't add the support package Fragment to an Activity as it will cause an Exception to be thrown.

    - Annotation: 
    	+ http://o7planning.org/web/fe/default/vi/document/18678/huong-dan-su-dung-java-annotation
    	+ http://beginnersbook.com/2014/09/java-annotations/
    
