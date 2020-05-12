# [Gatling Load Testing](https://www.james-willett.com/gatling-load-testing-complete-guide/)

## About

From James Willett's article [Gatling Load Testing](https://www.james-willett.com/gatling-load-testing-complete-guide/)

## Commands

```shell script
mvn gatling:test -Dgatling.simulationClass=simulations.LoadSimulationDesign

mvn gatling:test -Dgatling.simulationClass=simulations.RuntimeParameters -DUSERS=10 -DRAMP_DURATION=5 -DDURATION=30
```
