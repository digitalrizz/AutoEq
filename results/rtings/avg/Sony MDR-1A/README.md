# Sony MDR-1A
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -5.1; 23 -5.4; 25 -5.7; 28 -6.0; 31 -6.2; 34 -6.2; 37 -6.1; 41 -6.1; 45 -6.0; 49 -6.0; 54 -5.9; 60 -5.9; 66 -6.0; 72 -6.1; 79 -6.4; 87 -6.7; 96 -7.0; 106 -7.2; 116 -7.2; 128 -7.0; 141 -6.6; 155 -6.0; 170 -5.3; 187 -4.5; 206 -3.9; 227 -3.6; 249 -3.9; 274 -2.9; 302 -1.9; 332 -1.4; 365 -1.1; 402 -1.1; 442 -1.2; 486 -1.6; 535 -2.0; 588 -2.4; 647 -2.6; 712 -2.8; 783 -2.8; 861 -3.0; 947 -3.0; 1042 -3.1; 1146 -3.1; 1261 -3.3; 1387 -3.6; 1526 -3.9; 1678 -4.3; 1846 -4.6; 2031 -4.7; 2234 -4.0; 2457 -2.5; 2703 -1.8; 2973 -1.6; 3270 -1.6; 3597 -0.9; 3957 -4.0; 4353 -3.8; 4788 -0.5; 5267 -1.2; 5793 -0.8; 6373 -0.6; 7010 -1.2; 7711 -4.5; 8482 -9.7; 9330 -10.9; 10263 -6.5; 11289 -3.5; 12418 -3.5; 13660 -3.5; 15026 -3.5; 16529 -3.5; 18182 -6.2; 20000 -6.7
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-1A GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-1A ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.0dB**.

| Type    | Fc      |     Q | Gain     |
|:--------|:--------|:------|:---------|
| Peaking | 34 Hz   |  0.71 | -2.4 dB  |
| Peaking | 115 Hz  |  1.08 | -3.6 dB  |
| Peaking | 387 Hz  |  1.38 | 2.9 dB   |
| Peaking | 6958 Hz |  1.11 | 4.9 dB   |
| Peaking | 8905 Hz |  3    | -11.6 dB |
| Peaking | 1959 Hz |  2.9  | -2.1 dB  |
| Peaking | 3283 Hz |  1.72 | 2.3 dB   |
| Peaking | 4202 Hz |  4.85 | -3.7 dB  |
| Peaking | 4906 Hz | 12.48 | 2.0 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.1dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -2.5 dB |
| Peaking | 62 Hz    | 1.41 | -1.7 dB |
| Peaking | 125 Hz   | 1.41 | -3.8 dB |
| Peaking | 250 Hz   | 1.41 | 1.0 dB  |
| Peaking | 500 Hz   | 1.41 | 2.1 dB  |
| Peaking | 1000 Hz  | 1.41 | 0.0 dB  |
| Peaking | 2000 Hz  | 1.41 | -1.2 dB |
| Peaking | 4000 Hz  | 1.41 | 3.2 dB  |
| Peaking | 8000 Hz  | 1.41 | -2.8 dB |
| Peaking | 16000 Hz | 1.41 | -0.5 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Sony%20MDR-1A/Sony%20MDR-1A.png)