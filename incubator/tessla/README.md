 To run this very basic rpoof of concept, from this directory start the tessla-telegraf-connector:
```
./TesslaTelegrafConnector -i ./incubator.tessla -c ./telegraf.conf -r
```

then start telegraf:
```
  telegraf --config telegraf.conf
```