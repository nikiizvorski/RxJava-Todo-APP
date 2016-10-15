# RxJava-Todo-APP
RxJava Todo App using the library RxJava and Butterknife to remove the boilerplate code

EventBus and RxJava are different in their nature.

EventBus is just a bus as the name suggest - it provides the mechanism to subscribe and publish events to the "bus", without you caring how the wiring is done, what this "bus" actually is, etc. In the context of Android, the EventBus is just an easier way to deal with sending and receiving Broadcast messages with less boilerplate.

RxJava on the other hand is much much more powerful than that. Yes, you can subscribe and publish events, but you have far more control over the process - frequency, on which thread everything happens, etc. The main power of RxJava (in my opinion) is that you can manipulate the data being published very easy, using some of it's tons of operators.

To sum up - if you only care about publishing some events and performing some actions when received - you'd probably be better off using the simplest of the two, namely some kind of Bus, or even plain old BroadcastReceivers. If you will also benefit of transforming the data, handling threading or simplified error handling - go for the RxJava approach. Just keep in mind that RxJava generally has a steep learning curve, so it takes some time to get used to it's concept.

![RxJava](http://image.slidesharecdn.com/mobgen-fridaypresentation-160530082602/95/mobgen-android-session-mvp-rx-23-638.jpg?cb=1464596840)

You can get basic understanding how RxJava works and you can use the rxmarbles website to see how everythink works:

http://rxmarbles.com/

RxJava library the basic concept about is to remove all boilerplate code from the App and replace the whole logic with Subscribe and Unsubscribe elements easely remove the listeners with the Observer and the Observable this library can save a lot of time and code. Let say you have a big project and someone else have to come and work on that project he will just come check the code and move on with it, but if you dont use that library you will have probably a lot lines of code which are going to be very hard to test and very hard to someone who will just come that project to understand. Its just time consuming.

## Getting Started

You will have to download the project and run it on your local machine.

### Prerequisities

Everything you need in order to use this code is inside the project you may only need to update the gradle plugin and the libs.

## Built With

AndroidStudio 2.0 it will be builded with Gradle.

## Authors

* **Niki Izvorski ** - *Initial work*
