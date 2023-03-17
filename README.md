# Flutter Reference
## History of Flutter (by Tadas Petra)
https://www.youtube.com/watch?v=nGd6ryAFtIM

## Docs & Tutorials
flutter.dev/docs , Medium.com, YouTube.com, raywenderlich.com  
## Interview questions.  
#1 https://github.com/whatsupcoders/Flutter-Interview-Questions  
-Explain the Stateful Widget Lifecycle?  
-Why is the build() method on State and not StatefulWidget?  
#2 https://www.raywenderlich.com/10971345-flutter-interview-questions-and-answers  
*Focus on the following*.  
-How does Flutter run the code on Android & iOS?  
-What is SafeArea in flutter?  
-Explain different null operators in Dart.  
-What do you know about Dart Isolates?  
-Explain why the Fat Arrow operator is used in Flutter?  
-What are slivers? whats the different between slivers and ListView/GridView.. etc ?  
-How can we embed a regular widget (e.g., a container) within a sliver?  
-What are tween animations?  
-What are keys, and when do you use them?  
-How do you execute code only in certain modes (release, debug, profile)?  
-When do you use 'double.infinity’?  
-How do you override the back-button action?  
-What’s Flutter tree shaking?  
-Is Flutter actually native?  

#3 https://medium.com/@artrmz/flutter-interview-questions-and-answers-2020-adad5dacaf6a  
#4 https://github.com/power19942/flutter-interview-questions  

# Additional Questions  (Advanced). 
-Whats the different between dependencies and dev_dependencies in pubspec.yaml?  
-mention a couple of testing procedures in dart / flutter !  
-have you used DataClasses(DTO) in dart ? how do you create them?  
-tell us about what is functional programming and how to use it in dart?  
-Define External Functions?  
-talk about dart generators? (sync*,async*, yeild & yeild*)  
-why do we use asserts and when?  
-whats the different between throw and rethrow?  
-Have you heard about The "covariant" keyword? describe with small example.  
-whats deferred imports do?  
-whats hide in imports do?  
-whats [SOLID](https://en.wikipedia.org/wiki/SOLID "SOLID") and [DRY](https://www.plutora.com/blog/understanding-the-dry-dont-repeat-yourself-principle "DRY") principles 
<details>
<summary>what is JIT and AOT</summary>

In the context of the Dart programming language, JIT (Just-In-Time) and AOT (Ahead-Of-Time) compilation strategies are used to optimize the performance of the Dart code.

JIT (Just-In-Time) Compilation: In Dart, JIT compilation is employed during development to enable features like hot-reloading, which allows developers to see the changes in their code without needing to restart the application. JIT compilation provides faster development cycles, but the compiled code may not be as optimized for performance as AOT-compiled code.

AOT (Ahead-Of-Time) Compilation: Dart uses AOT compilation when building a production version of the application. AOT compilation compiles the Dart code into native machine code before the application is run, which results in faster startup times and improved performance. AOT compilation also enables smaller executable sizes and better memory usage. However, AOT-compiled code lacks the hot-reloading feature available during development with JIT compilation.

In summary, Dart uses JIT compilation during development to provide a better development experience with features like hot-reloading, while it uses AOT compilation for production builds to deliver better performance and smaller executable sizes.

</details>


