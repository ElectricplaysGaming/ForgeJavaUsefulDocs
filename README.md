# ForgeJavaUsefulDocs
My Basic Java Docs for beginners (beginning of my journey)

## Event handler that registers itself
 ```java
@Mod.EventBusSubscriber
public class MyEventHandler {
    @SubscribeEvent
    public static void myEvent(Event event) {
    //Code Here
    }
}
```
