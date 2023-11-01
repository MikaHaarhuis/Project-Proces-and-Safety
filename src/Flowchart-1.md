```plantuml
@startuml

start

repeat
:Check row for parts;
    if (Parts detected?) then (no)
      #red:Error missing part;
      kill
    endif
    ->yes;
    :All parts availible;
repeat while (row 5 checked?) is (no) not (yes)
:Move to next row;
-> yes
:Proceed;

stop


@enduml