# Jet printer waste ink counter modification tool

## Supported printers

* Epson EcoTank L3160

## Counter modification tool

```sh
npm run count <ip-addr> dev             # Get device info
npm run count <ip-addr> get             # Get counter values in percents
npm run count <ip-addr> set <c1> <c2>   # Set counter values in percents
```

You can parse captures like this:

```sh
npm run parse capture/dev.json
npm run parse capture/get.json
npm run parse capture/set.json
```
