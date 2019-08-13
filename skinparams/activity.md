# Activity


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
            <td><code>Background</code></td>
            <td><code>Color</code></td>
            <td><img
                    src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/master/skinparams/activity/background.txt"
                    alt="0"/></td>
<td>

```puml
@startuml
skinparam ActivityBackgroundColor Green
start
:foo;
stop
@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Bar</code></td>
            <td><code>Color</code></td>
            <td><img alt="1" src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/master/skinparams/activity/bar.txt"/></td>
<td>

```puml
@startuml
skinparam ActivityBarColor Green
start
fork
:foo;
fork again
:bar;
end fork
stop
@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Border</code></td>
            <td>
                <code>Color</code><br/>
                <code>Thickness</code>
             </td>
            <td><img alt="2" src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/master/skinparams/activity/border.txt"/></td>
<td>

```puml
@startuml
skinparam ActivityBorder {
  Color Green
  Thickness 5
}
start
:foo;
stop
@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Diamond</code></td>
            <td>
                <code>BackgroundColor</code><br/>
                <code>BorderColor</code><br/>
                <code>Font*</code>
            </td>
            <td><img alt="3" src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/master/skinparams/activity/diamond.txt"/></td>
<td>

```puml
@startuml
skinparam ActivityDiamond {
  BackgroundColor LightBlue
  BorderColor Blue
  Font {
    Color DarkBlue
    Name Arial
    Size 18
    Style Bold
  }
}
start
if (isFoo) then (foo)
  :doFoo;
else (bar)
  :doBar;
endif
stop
@enduml
```
</td>
        </tr>
        <tr>
            <td><code>End</code></td>
            <td><code>Color</code></td>
            <td><img alt="4" src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/master/skinparams/activity/end.txt"/></td>
<td>

```puml
@startuml
skinparam ActivityEndColor Green
start
:foo;
stop
@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Font</code></td>
            <td>
                <code>Color</code><br/>
                <code>Name</code><br/>
                <code>Size</code><br/>
                <code>Style</code>
            </td>
            <td><img alt="5" src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/master/skinparams/activity/font.txt"/></td>
<td>

```puml
@startuml
skinparam ActivityFont {
  Color DarkBlue
  Name Arial
  Size 18
  Style Bold
}
start
:foo;
stop
@enduml
```
</td>
        </tr>
        <tr>
            <td colspan="2">
            <span><code>Shape</code><br/><small>not supported in Activity Beta syntax</small></span></td>
            <td><img alt="7" src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/master/skinparams/activity/shape.txt"/></td>
<td>
        
```puml
@startuml
skinparam Activity {
  Shape<<Foo>> Octagon
  Shape<<Bar>> RoundBox
}
(*) --> "foo" << Foo >>
"foo" --> "bar" << Bar >>
"bar" --> (*)
@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Start</code></td>
            <td><code>Color</code></td>
            <td><img alt="6" src="http://www.plantuml.com/plantuml/proxy?fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/master/skinparams/activity/start.txt"/></td>
<td>

```puml
@startuml
skinparam ActivityStartColor Green
start
:foo;
stop
@enduml
```
</td>
        </tr>
    </tbody>
</table>
