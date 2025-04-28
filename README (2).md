# API Reference



## Events

<table data-card-size="large" data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td>Name: GeneratorEvent </td><td>Description: Anything to do with a generator.</td><td></td></tr><tr><td>Name: GeneratorGenerateEvent </td><td>Description: Whenever a generator generates an item.</td><td></td></tr><tr><td>Name: GeneratorPlaceEvent</td><td>Description: When a generator gets placed. (Player/Server/Command)</td><td></td></tr><tr><td>Name: GeneratorInteractEvent </td><td>Description: When a Player, se4rver, or command interacts with an item.</td><td></td></tr></tbody></table>



### How to use the events

View the JavaDoc for more detailed information on the methods and implementation.

```java
public class MyEvent implements Listener {
    @Override
    public void onGeneratorEvent(GeneratorEvent event) {
        Generator generator = event.getGenerator();
        Player genOwner = generator.getOwner()
        Player player = event.getPlayer();
    }
}
```
