# Digital Clock Using 555 Timer and 74LS90 
> This digital clock uses a 555 timer to generate the clock signal, 4013 flip-flops to select and adjust the time using buttons, and 74LS90 counters to count and display hours, minutes, and seconds on 7-segment displays.

![Digital Clock Circuit Schematic](https://github.com/youness-el-kabtane/Digital-Clock-Using-555-Timer-and-74LS90-/blob/aa4caa3c8b655305bed3794e3f4025049be36034/Digital%20Clock/Screenshot.png)

## Important Datasheets & References 

### 74LS90 (decade/binary counter) - [See Datasheets](https://www.ti.com/lit/ds/symlink/sn54ls90.pdf?ts=1764269333572)

The 74LS90 datasheet describes it as a decade/binary counter made up of four master-slave flip-flops. It supports divide-by-2 and divide-by-5 (or divide-by-10 via proper wiring) modes, and includes gated reset inputs. 

### CD4013B (dual D-type flip-flop — 4013) - [See Datasheets](https://www.ti.com/lit/ds/symlink/cd4013b.pdf?ts=1764343671027&ref_url=https%253A%252F%252Fwww.google.com%252F)

The CD4013B has two independent D-type flip-flops, each with data, clock, asynchronous set and reset inputs, and Q / Q̄ outputs. Operating voltage ranges from about 3 V to 18 V. 

### NE555 (timer/oscillator) - [See Datasheets](https://www.ti.com/lit/ds/symlink/ne555.pdf)

The NE555 is a widely used timer/oscillator IC. It supports astable (oscillator) and monostable/timer modes, with a typical supply range around 4.5–16 V (depending on variant).

### 74-series Logic / AND-OR Gates (TTL) - [See Datasheets](https://www.futurlec.com/IC74LS00Series.shtml)

For AND, OR, and other logic gates you can use standard 74-series (or 74LS) TTL logic ICs. Many datasheet collections covering the entire 74-series exist — useful when combining counters, gates, and flip-flops. 
