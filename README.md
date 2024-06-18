# API Reference



## Events

<table data-card-size="large" data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td>Name: GeneratorEvent </td><td>Description: Anything to do with a generator</td><td></td></tr><tr><td>Name: GeneratorGenerateEvent </td><td>Description: Anything to do with a generator</td><td></td></tr><tr><td>Name: GeneratorGenerateEvent </td><td>Description: Anything to do with a generator</td><td></td></tr><tr><td>Name: GeneratorPlaceEvent</td><td>Description: Anything to do with a generator</td><td></td></tr><tr><td>Name: GeneratorInteractEvent </td><td>Description: Anything to do with a generator</td><td></td></tr></tbody></table>



### How to use the events

View the JavaDoc for more information on how&#x20;

```java
public class MyEvent implements Listener {
    @Override
    public void onGeneratorEvent(GeneratorEvent event) {
        Generator gen = event.getGenerator();
        Player player = event.getOwner();
    }
}
```
