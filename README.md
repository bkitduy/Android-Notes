# Android-Notes
 Android
  - Native : 
  	+ Java (Android Studio, Eclipse)-OOP 
  	+ Kotlin (Android Studio, Intellij IDE)- OOP and Structure 
  	+ Scala (Intellij IDE)-OOP and Structure
  	+ 
  - Cross platform
  	+ PhoneGap
  	+ Titanium
  	+ React Native
  	
A. Native

I. Java
 1. Language and IDE
   Write with Java (currently Java 7 and supported Java 8) and write on Android Studio and Eclipse IDE
 2.	Database local:
  -  SQLite (SQL):
	  + Can use some framework ORM (Sugar ORM?) to convert data from database to object model in OOP
	  + greenDao: http://lomza.totem-soft.com/tutorial-how-to-integrate-greendao/
	  	      https://www.youtube.com/watch?v=zDdu1MlXjZw
  - Realm (SQL):
	  + https://realm.io/docs/java/latest/
  - SQLighter (SQL):
	  + https://github.com/vals-productions/sqlighter
  - Couchbase Lite (NoSQL)

 3.	Other Libraries:
  - GSON : Parse JSON- https://github.com/google/gson
  - Hackson-databind: https://github.com/FasterXML/jackson-databind
  - Otto: http://square.github.io/otto/
  - EventBus : https://medium.com/@cainwong/using-an-eventbus-in-android-pt-1-why-an-eventbus-c2c9cdff41d7#.u1s04p9gh 
  - Parceler (base on Parcelable): https://github.com/johncarl81/parceler
  - Retrofit/Volley : Network calls
    + http://laptrinhandroid.xyz/2015/09/16/gioi-thieu-retrofit-2-0-a-type-safe-http-client-for-android/
    + http://code.tutsplus.com/tutorials/an-introduction-to-volley--cms-23800
  - Robolectric
  - Rx Java, Android: 
    http://x-team.com/2016/02/introduction-reactivex-android/ 
  - Others you can find here: https://android-arsenal.com/
  
  3.1	Design Pattern:
    - Creational Pattern (Khởi tạo object): Builder, Abtract Factory, Factory Method, Singleton, Prototype
    - Structural Pattern (Thiết lập, định nghĩa quan hệ giữa các object): Adapter, Bridge, Composite, Decorator, Façade, Proxy, Flyweight
    - Bahavioral Pattern (Dùng trong thực hiện các hành vi của object): Interpretor, Iterator, Observer,Template Method, Chain of Responsibility, Command, Mediator, Memento, State, Startegy and Visitor
    - References:
    	+ http://laptrinh.vn/d/4346-design-pattern-la-gi-huong-dan-design-pattern.html
    - MVP: http://hannesdorfmann.com/mosby/mvp/
    
  3.2	Notes:
    - Best practice Android: https://github.com/futurice/android-best-practices#java-packages-architecture
    - Save States Fragment/Activity: http://inthecheesefactory.com/blog/fragment-state-saving-best-practices/en
    - Style writing: http://www.google.com/design/spec/style/writing.html#writing-capitalization-punctuation
    - http://saulmm.github.io/avoding-android-cold-starts
    - Memory leak: http://daynhauhoc.com/t/memory-leak-nguyen-nhan-gay-leak-trong-android/11343
    - http://blog.appconus.com/2015/08/16/memory-leak-trong-android-nguyen-nhan-va-cach-xu-ly-phan-1/

  3.3	Awesome libraries
    - UX/UI: https://github.com/wasabeef/awesome-android-ui
    - Libraries: https://github.com/wasabeef/awesome-android-libraries
    - https://snowdream.github.io/awesome-android/
    
  3.4   Some explains:
    - Fragment: 
    	+ A Fragment must always be embedded in an Activity
    	+ Use android.app.Fragment with Activity
    	
    - FragmentActivity:
    	+ Use the FragmentActivity to hold your Fragments
    	+ Use android.support.v4.app.Fragment with FragmentActivity
    	
    Don't add the support package Fragment to an Activity as it will cause an Exception to be thrown.
    
    - Fragment transitions with shared elements: https://medium.com/@bherbst/fragment-transitions-with-shared-elements-7c7d71d31cbb#.mqmwvhldz
    
    - Annotation: 
    	+ http://o7planning.org/web/fe/default/vi/document/18678/huong-dan-su-dung-java-annotation
    	+ http://beginnersbook.com/2014/09/java-annotations/
    	
    - Android : http://icetea-vn.blogspot.com/search/label/Android
    
    - Android thread: 
    	+ "background" or "worker" threads (same)
    	+ UI thread or main thread (same)
 4. Some bug may occur on Gradle
 
  4.1 Gradle sync failed: 
    - Cause: org/gradle/api/publication/maven/internal/DefaultMavenFactory
   
       + if your "gradle.properties" file which is located at the root level of your project contains :
	
	 classpath 'com.github.dcendents:android-maven-plugin:1.2',
	
	 try to change to:
	
	 classpath 'com.github.dcendents:android-maven-gradle-plugin:1.3'

	 And change classpath 'android-maven'
	
	 to classpath

 	 apply plugin: 'com.github.dcendents.android-maven'
 
 5. Some plugins support fast coding:
 
  5.1 Android DPI Caculator

  5.2 Android Material Design Icon Generator Plugin
  
  5.3 Android Parcelable Code Generator
  
  5.4 CheckStyle
  
  5.5 9-Patch-Resizer: https://github.com/redwarp/9-Patch-Resizer/releases
 
	--------------------------------- Coming soon ------------------------------------------
    
II. Kotlin
  1. Language and IDE
  	Kotlin language and you can write on Android Studio IDE with plugin Kotlin or Intellij IDE
  2. Some tutorials:
  	- http://cirorizzo.net/2016/03/04/building-a-kotlin-project/
  	
	
	-------------------------------- Coming soon -----------------------------------------

B. CrossPlatform

I. React Native

	--------------------------- Coming soon ------------------------------------------
 
