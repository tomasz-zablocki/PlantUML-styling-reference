# Activity

<table>
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
            <td><code>BackgroundColor</code></td>
            <td><img
                    src="http://www.plantuml.com/plantuml/proxy?idx=0&fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/activity.txt"
                    alt="0"/></td>
<td>

```puml
@startuml

skinparam Activity {
    BackgroundColor Green
}

start
:foo;
end

@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Bar</code></td>
            <td><code>BarColor</code></td>
            <td><img alt="1" src="http://www.plantuml.com/plantuml/proxy?idx=1&fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/activity.txt"/></td>
<td>

```puml
@startuml

skinparam Activity {
    BarColor Green
}

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
                <code>BorderColor</code><br/>
                <code>BorderThickness</code>
             </td>
            <td><img alt="2" src="http://www.plantuml.com/plantuml/proxy?idx=2&fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/activity.txt"/></td>
<td>

```puml
@startuml

skinparam Activity {
    BorderColor Green
    BorderThickness 5
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
                <code>DiamondBackgroundColor</code><br/>
                <code>DiamondBorderColor</code><br/>
                <code>DiamondFontColor</code><br/>
                <code>DiamondFontName</code><br/>
                <code>DiamondFontSize</code><br/>
                <code>DiamondFontStyle</code>
            </td>
            <td><img alt="3" src="http://www.plantuml.com/plantuml/proxy?idx=3&fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/activity.txt"/></td>
<td>

```puml
@startuml

skinparam Activity {
    DiamondBackgroundColor LightBlue
    DiamondBorderColor Blue
    DiamondFontColor DarkBlue
    DiamondFontName Arial
    DiamondFontSize 18
    DiamondFontStyle Bold
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
            <td><code>EndColor</code></td>
            <td><img alt="4" src="http://www.plantuml.com/plantuml/proxy?idx=4&fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/activity.txt"/></td>
<td>

```puml
@startuml

skinparam Activity {
    EndColor Green
}

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
                <code>FontColor</code><br/>
                <code>FontName</code><br/>
                <code>FontSize</code><br/>
                <code>FontStyle</code>
            </td>
            <td><img alt="5" src="http://www.plantuml.com/plantuml/proxy?idx=5&fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/activity.txt"/></td>
<td style="text-align: center">

```puml
@startuml

skinparam Activity {
    FontColor DarkBlue
    FontName Arial
    FontSize 18
    FontStyle Bold
}

start
:foo;
stop

@enduml
```
</td>
        </tr>
        <tr>
            <td><code>Start</code></td>
            <td><code>StartColor</code></td>
            <td><img alt="6" src="http://www.plantuml.com/plantuml/proxy?idx=6&fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/activity.txt"/></td>
<td style="text-align: center">

```puml
@startuml

skinparam Activity {
    StartColor Green
}

start
:foo;
stop

@enduml
```
</td>
        </tr>
        <tr>
            <td>
            <code>Shape</code><br/>
            </td>
            <td><code>Shape</code><br/></td>
            <td><img alt="7" src="http://www.plantuml.com/plantuml/proxy?idx=7&fmt=svg&cache=no&src=https://raw.githubusercontent.com/tomasz-zablocki/plantuml-theme-reference/wip/skinparams/activity.txt"/></td>
<td style="text-align: center">
<span style="padding: 0.3rem; font-style: italic; font-size: 0.5rem">not supported in Activity Beta syntax</span>

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
    </tbody>
</table>
