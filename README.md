# -12-V-DC-Input-Protection-Diode-Selection


## Selected Diode
1N4007 rectifier diode

## Justification

### Voltage Rating
The 1N4007 has a maximum repetitive reverse voltage of **1000 V**, which is far higher than the required 12 V input. This large safety margin ensures reliable protection against reverse polarity and voltage spikes.

### Current Rating
The diode is rated for a maximum average forward current of **1 A**, which is sufficient for a simple low-power 12 V DC input. This makes it suitable for protecting small electronic devices from accidental reverse connection.

### Cost and Availability
The 1N4007 is inexpensive and widely available from most electronics suppliers. Because it is a standard rectifier diode, it is commonly stocked and easy to replace, making it a practical choice for real-world designs.

### Simulation in LTspice
The diode was simulated in series with a 12 V DC source and a load resistor. In normal operation, the diode conducts and allows current to flow to the load. When the input polarity is reversed, the diode blocks current, protecting the circuit from damage.

## Conclusion
The 1N4007 diode is a suitable and cost-effective choice for a simple 12 V DC input protection circuit due to its high voltage rating, adequate current capacity, and wide availability.
