# Quadrature Encoder Interface (QEI)

Simple library for quadrature digital encoders. Written for the Pololu 37D 64 bit encoder, but should be usable for different motors too.

Class was originally written for the K64F with MBED-OS. However, the code should be generic enough for any platform.

## Example

```c++

QEI encoder(D11, D12);

int y = encoder.pulses();
```

## Credits

Code was originally written by Aaron Berk.