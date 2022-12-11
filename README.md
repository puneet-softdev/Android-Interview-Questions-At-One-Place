# Android-Interview-Questions
All Android Interview Questions at One Place

My Personal Experience with Many Companies
A set of questions that I have accumulated over these 6.5 Years in preparation for my many Android Interviews Prep. I hope this will help everyone out here both for those who are looking for Job and also for those who want to Brush up their skills :)
Hence sharing with you all

I will tell the most important and commonly asked questions First so that you can prepare accordingly

— — — — — — — — — Activity/Fragment Part — — — — — — —

Explain Activity Life Cycle and Most Importantly What will be the Life cycle (In Order) If Activity B is Launched from Activity A.
Explain Fragment Life Cycle, How the Activity Life cycle and Fragment Life Cycle gets called In Order, RetainInstanceState in Fragment
Fragment Add vs Fragment Replace, Explain with using Backstack and Without using backstack
Activity Life cycle when Dialog is opened — (hint:- Don’t get confused b/w system-generated Dialog and your own app dialog)
Why to use setContentView() in onCreate() callback method?
LaunchModes in Android. What is onNewIntent (Very very important to understand it)
Why it is recommended to use Default Constructor to create a Fragment

— — — — — — — Let’s move on to Service Part — — — — — — —

On Which Thread Services Work? What are the Changes and Limitations introduced in the latest version of android regarding Services
Services vs Intent Services — (Other than the Thread on which these both works 😜)
Foreground Services and Background Services, Work Manager Role
How Work Manager, Job Intent Service, Alarm Manager, Firebase Dispatcher are correlated, Which to use when

— — — — — — — — Broadcast Receiver — — - — — — —

What’s Static and Dynamic Broadcast Receiver, What’re the changes Introduced in Latest version of Android regarding broadcast Receiver (hint:- Study Local Broadcast Manager)

— — — — — — — — — Content Provider — — — — —

Explain Content Provider, What is Scheme? How can an Application Access database of another Application

— — — —— — — MVVM Design Pattern — — — — — —

Design Pattern vs Architecture? Explain MVVM Design Pattern
MVVM vs MVP Design Pattern (Nowadays MVI Design Pattern too)
How ViewModel save Instance of UI? What’s the Role of Live Data in it, How Live data is different from Observer-Observable Pattern
How will you write your own ViewModel if Android ViewModel is not there
SharedViewModel, How to use it in Master-Detail kind scenarios for Fragment communication i.e Bye Bye Interface for Communication
How UI state is managed with ViewModel, savedInstanceState, and Database?
How to pass data in ViewModel constructor (hint:- ViewModel Factory)
LiveData vs Mutable Live Data vs Mediator Live Data
Map vs Switch Map in LiveData

— — — — — RxJava in Android (Event-Based) — — — — — -—

Explain RxJava? What are Observables and Observers?
Operators in RxJava. Map vs FlatMap in RxJava
Subject in RxJava? Implement Own EventBus by RxJava
How to implement Searching by RxJava
Hang On ! Hope you have got huge knowledge Now. Let’s learn something which is equally important as the topics we studied above. It will worth your time

— — — — — Threading in Android (Do Study this one too )— — —

Runnable vs Thread, the Basic difference between these two
If Java already have threads/multi-threading Architecture than why Android needs to implement Handler
What is Yarn, Join function. Sleep() vs Wait() in Threading (Usually asked in all companies)
How can you implement Synchronization? Object Level lock vs Class Level Lock
Thread Pool Executor (Must study if not heard of this). Explain ArrayBlockingQueue?
Synchronize Keyword vs Synchronized Block (Very basic difference)

— — -— Mixup and Most Important Interview Questions — —

ViewBinding vs DataBinding in Android, What is Binding Adapter? What’s the use of data tag in XML
What is Dagger in Android? Implement own Manual Dependency Injection without Dagger, What is Module and Submodule in Dagger
Build Type in Gradle? Explain Flavors in Gradle
Handler, Looper, Handler vs HandlerThread
Intent, Sticky Intent, Pending Intent. Purpose of Category in Intent
And yohooo……! Thanks for Reading
This the experience I thought to share with you all, This list is by no means exhaustive. I will appreciate your thoughts on these questions in responses