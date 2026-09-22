# JMeter Non-GUI Execution

A compact performance-testing exercise demonstrating Apache JMeter execution from the command line.

## Included

- `NonGUI.jmx` — test plan
- `Results.jtl` and `Results.csv` — recorded execution results
- `jmeter.log` — sample runtime log

## Run

```bash
jmeter -n -t NonGUI.jmx -l Results.jtl
```

Generate an HTML dashboard:

```bash
jmeter -g Results.jtl -o report
```

Only run performance tests against systems for which you have explicit authorisation.
