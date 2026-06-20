# Common Drain Amplifier

## Objective

To design and simulate a Common Drain Amplifier (Source Follower) using NMOS transistors and study its frequency response characteristics.

## Theory

A Common Drain Amplifier is also known as a Source Follower.

In this configuration:

- Input is applied to the gate.
- Drain is connected to the supply voltage.
- Output is taken from the source.

The circuit provides:

- High input impedance
- Low output impedance
- Voltage gain close to unity

## Circuit Operation

When an input signal is applied to the gate terminal, the source voltage follows the input voltage while maintaining approximately one threshold voltage difference.

As a result, the output closely tracks the input signal.

## Simulation

AC analysis was performed over a wide frequency range.

Frequency Range:
100 Hz to 10 GHz

Supply Voltage:
5 V

## Working Principle

When an input signal is applied to the gate of the NMOS transistor:

1. The transistor operates in the saturation region.
2. Source voltage follows the gate voltage.
3. Output is produced at the source terminal.
4. The lower NMOS provides bias current.
5. The output tracks the input with approximately unity gain.


### Inputs and Outputs

| Signal | Description |
|----------|------------|
| Vin | Input Signal |
| Vb | Bias Voltage |
| Vout | Output Signal |
| VDD | Supply Voltage |

# Layout Features:

- NMOS transistor implementation
- Metal interconnections
- Input and output routing
- Power and ground connections
- DRC clean layout


## Observations

- Stable response at low frequencies.
- Gain remains close to unity.
- Frequency response changes at higher frequencies due to parasitic effects.

## Conclusion

The Common Drain Amplifier successfully demonstrates source follower behavior and is useful for buffering and impedance matching applications.