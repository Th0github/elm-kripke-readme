# Kripke Model Visualizer


This help page has been accessed with with the following commands
```
fetchedReadMe : Cmd Msg
fetchedReadMe =
    Http.get
        { url = "https://raw.githubusercontent.com/elm/browser/master/README.md"
        , expect = Http.expectString RecieveReadMe
        }
```
