# reader-dump

This is dump of ATMEGA168PA MCU (AVR-8) from tehtel (whitelabel). 

For some reason, it can be opened using EM4100 card with FF:FF:FF:FF:FF ID.

## Using radare2 to look at assembly

```bash
r2 -a avr reader.img
```

## Dumping

```
minipro --device ATMEGA168PA@MLF32 --read reader.img
```
