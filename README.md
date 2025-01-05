# FeatherWing_dual_TMC2300

FeatherWing with two [TMC2300 (Low voltage silent stepper motor driver)](https://www.analog.com/en/products/tmc2300.html)

alternative you can use the [_breakout board_](https://www.reichelt.de/de/de/shop/produkt/breakout_board_fuer_tmc2300_schrittmotor-treiber-284703)

## ToDo

-   find FeatherWing template for kicad
    -   https://gitlab.com/kicad/libraries/kicad-templates/-/tree/master/Projects?ref_type=heads
    -   https://github.com/whmountains/FeatherWing-template-KiCad
    -   https://github.com/mignon-p/FeatherWing-template-KiCad/tree/master/FeatherWing_KC5
-   finalize schematics
    - check power-options with Feather Specification
    -   address selection
    -   sens resistors
    -   connectors
    -   pin mapping
    -   check with support for protection
    - maybe add a cheap I2C acceleromater sensor
-   add FeatherWing template
-   layout board

<!-- file format / software information -->

## used software:

KiCad 8.0

```
Application: KiCad x86_64 on x86_64
Version: 8.0.7-8.0.7-0~ubuntu24.04.1, release build
Platform: Ubuntu 24.04.1 LTS, 64 bit, Little endian, wxGTK, X11, KDE, x11
```

Inkscape 1.2

# License

<!-- license info -->
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
    <img alt="Creative Commons License" style="border-width:0"
        src="https://i.creativecommons.org/l/by/4.0/88x31.png" />
</a>
<br />
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">
    all files in FeatherWing_dual_TMC2300
</span> by
<a xmlns:cc="http://creativecommons.org/ns#"
        href="https://github.com/s-light/FeatherWing_dual_TMC2300"
        property="cc:attributionName"
        rel="cc:attributionURL">
    Stefan Krüger (s-light)
</a>
are licensed under a<br/>
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
    Creative Commons Attribution 4.0 International License
</a>.

all software parts/files are licensed under [MIT](LICENSE).

i see this project as [Open Source Hardware (OSHW)](https://www.oshwa.org/definition/)

![OSHW logo](http://www.oshwa.org/wp-content/uploads/2014/03/oshw-logo.svg)

<!-- license info end -->

---

<style>
    img {
        max-width: 80vw;
        max-height: 70vh;
    }
</style>
