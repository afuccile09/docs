# docs

@startuml
participant Selenium
participant LocalSkyUI
participant Reader
Selenium -> LocalSkyUI: Request
LocalSkyUI -> Reader: Request
Reader -> LocalSkyUI: Response
LocalSkyUI -> Selenium: Response
@enduml
