# Class

<table xmlns="http://www.w3.org/1999/html">
    <thead>
    <tr>
        <th>Group</th>
        <th>skinparam</th>
        <th>Diagram</th>
        <th>Source</th>
    </tr>
    </thead>
    <tbody>
<tr>
            <td><code>Arrow</code></td>
            <td><code>Color</code><br/><code>Font*</code></td>
            <td><img
                    src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/class/arrow.txt"
                    alt="0"/></td>
<td>

```puml
@startuml
skinparam ClassArrow {
  Font {
    Color DarkBlue
    Name Arial
    Size 18
    Style Bold
  }
  Color Blue
}
class Foo
class Bar
class FooBar
Foo <|-down- Bar: FooLike
Foo "1" *-up- "many" FooBar: fooBars
@enduml
```
</td>
    </tr>
<tr>
            <td><code>Attribute</code></td>
            <td><code>Font*</code><br/><code>IconSize</code></td>
            <td><img
                    src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/class/attribute.txt"
                    alt="0"/></td>
<td>

```puml
@startuml
skinparam {
  ClassAttribute {
    Font {
        Color DarkBlue
        Name Arial
        Size 22
        Style Bold
    }
    IconSize 22
  }
  Padding 20
}
class Foo {
  +Int Bar
}
@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Background</code></td>
            <td><code>Color</code></td>
            <td><img
                    src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/class/background.txt"
                    alt="0"/></td>
<td>

```puml
@startuml
skinparam ClassBackgroundColor Blue\Green
class Foo {
}
@enduml
```
</td>
    </tr>
    <tr>
                <td><code>Border</code></td>
                <td><code>Color</code><br/><code>Thickness</code></td>
                <td><img
                        src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/class/border.txt"
                        alt="0"/></td>
<td>
    
```puml
@startuml
skinparam ClassBorder {
  Color Green
  Thickness 5
}
class Foo {
}
@enduml
```
</td>
        </tr>
            <tr>
            <td><code>Font</code></td>
            <td><code>Color</code><br/><code>Name</code><br/><code>Size</code><br/><code>Style</code></td>
            <td><img
                    src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/class/font.txt"
                    alt="0"/></td>
<td>

```puml
@startuml
skinparam ClassFont {
  Color DarkBlue
  Name Arial
  Size 18
  Style Bold
}
class Foo {
}
@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Header</code></td>
            <td><code>Background*</code></td>
            <td><img
                    src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/class/header.txt"
                    alt="0"/></td>
<td>

```puml
@startuml
skinparam ClassHeaderBackgroundColor Green
class Foo {
}
@enduml
```
</td>
    </tr>
        <tr>
            <td><code>Stereotype</code></td>
            <td><code>Font*</code></td>
            <td><img
                    src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/class/stereotype.txt"
                    alt="0"/></td>
<td>

```puml
@startuml
skinparam ClassStereotypeFont {
Color DarkBlue
  Name Arial
  Size 18
  Style Bold
}
class Foo << Bar >> {
}
@enduml
```
</td>
        </tr>
    </tbody>
</table>




