# Grado GR 10
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -8.9; 23 -8.9; 25 -8.9; 28 -8.9; 31 -8.9; 34 -8.9; 37 -8.9; 41 -8.9; 45 -8.9; 49 -8.9; 54 -8.9; 60 -8.9; 66 -8.9; 72 -8.7; 79 -8.6; 87 -8.6; 96 -8.6; 106 -8.8; 116 -8.9; 128 -8.9; 141 -8.6; 155 -8.5; 170 -8.3; 187 -8.6; 206 -8.8; 227 -8.9; 249 -8.8; 274 -8.6; 302 -8.4; 332 -8.3; 365 -8.0; 402 -7.9; 442 -7.7; 486 -7.4; 535 -7.2; 588 -6.9; 647 -6.6; 712 -6.4; 783 -6.0; 861 -5.8; 947 -5.4; 1042 -5.1; 1146 -4.8; 1261 -4.5; 1387 -4.2; 1526 -4.0; 1678 -3.7; 1846 -3.5; 2031 -4.5; 2234 -6.3; 2457 -7.7; 2703 -8.7; 2973 -8.7; 3270 -6.6; 3597 -3.1; 3957 -4.3; 4353 -7.5; 4788 -7.5; 5267 -4.4; 5793 -1.3; 6373 -0.5; 7010 -3.4; 7711 -5.6; 8482 -5.9; 9330 -5.9; 10263 -5.9; 11289 -5.9; 12418 -5.9; 13660 -5.9; 15026 -5.9; 16529 -5.9; 18182 -5.9; 20000 -5.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Grado GR 10 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado GR 10 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.0dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 52 Hz   | 0.09 | -3.0 dB |
| Peaking | 1835 Hz | 0.9  | 6.2 dB  |
| Peaking | 3316 Hz | 0.86 | -9.6 dB |
| Peaking | 3654 Hz | 3.91 | 10.0 dB |
| Peaking | 6111 Hz | 2.94 | 8.6 dB  |
| Peaking | 168 Hz  | 4.2  | 0.5 dB  |
| Peaking | 232 Hz  | 2.72 | -0.5 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-2.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -3.0 dB |
| Peaking | 62 Hz    | 1.41 | -2.1 dB |
| Peaking | 125 Hz   | 1.41 | -2.1 dB |
| Peaking | 250 Hz   | 1.41 | -2.3 dB |
| Peaking | 500 Hz   | 1.41 | -1.5 dB |
| Peaking | 1000 Hz  | 1.41 | 1.5 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.4 dB  |
| Peaking | 4000 Hz  | 1.41 | -0.2 dB |
| Peaking | 8000 Hz  | 1.41 | 1.8 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Grado%20GR%2010/Grado%20GR%2010.png)