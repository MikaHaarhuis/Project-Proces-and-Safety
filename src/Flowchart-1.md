```plantuml
@startuml

start
    :Go to home position;
    :Check parts row 1;
if (part detected?) then (yes)
    :Check parts row 2;
else (no)
    :Go to home position;


@enduml