# EMONHUB

> Anticloud offline package — upstream: openenergymonitor/emonhub @ `master`.

## What This Project Does

Python service linking and decoding input to MQTT & Emoncms 

**Topics:** emoncms, mqtt, rfm12b, rfm12pi, rfm69cw, rfm69pi

## Upstream README

# emonHub

EmonHub is a piece of software running on the emonPi and emonBase that can read/subscribe or send/publish data to and from a multitude of services. It is primarily used as the bridge between the OpenEnergyMonitor monitoring hardware and the Emoncms software but it can also be used to read in data from a number of other sources, providing an easy way to interface with a wider range of sensors.

## Documentation

- [Overview](https://docs.openenergymonitor.org/emonhub/overview.html)
- [Configuration](https://docs.openenergymonitor.org/emonhub/configuration.html)
- [Interfacers](https://docs.openenergymonitor.org/emonhub/emonhub-interfacers.html)

Alternatively view the documentation directly on github here: [emonhub/docs](docs).

## Licence

GNU Affero General Public License

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
