The Switch form element is used for a toggle switch row.

## On and Off Values
The value is set to onValue when checked. The value is set to offValue when unChecked. 

## Example

### Kotlin
```kotlin
switch<String>(1) {
   value = "Yes"
   onValue = "Yes"
   offValue = "No"
}
```

### Java
```java
List<BaseFormElement<?>> elements = new ArrayList<>();
SwitchBuilder<String> switchElement = new SwitchBuilder<>(1);
switchElement.setValue("Yes");
switchElement.setOnValue("Yes");
switchElement.setOffValue("No");
elements.add(switchElement.build());
```