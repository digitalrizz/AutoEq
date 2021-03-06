# Sennheiser HD 800 S
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -1.0; 25 -1.4; 28 -2.0; 31 -2.4; 34 -2.8; 37 -3.1; 41 -3.4; 45 -3.6; 49 -3.8; 54 -4.0; 60 -4.1; 66 -4.2; 72 -4.4; 79 -5.0; 87 -5.7; 96 -6.2; 106 -6.7; 116 -7.0; 128 -7.4; 141 -7.6; 155 -7.8; 170 -7.8; 187 -8.1; 206 -8.1; 227 -8.1; 249 -8.1; 274 -8.0; 302 -7.9; 332 -7.8; 365 -7.6; 402 -7.4; 442 -7.2; 486 -7.1; 535 -6.9; 588 -6.5; 647 -6.3; 712 -6.2; 783 -5.7; 861 -5.6; 947 -5.3; 1042 -4.9; 1146 -4.6; 1261 -4.1; 1387 -3.7; 1526 -3.3; 1678 -3.5; 1846 -3.6; 2031 -3.3; 2234 -3.5; 2457 -3.0; 2703 -2.7; 2973 -3.2; 3270 -2.9; 3597 -3.6; 3957 -4.8; 4353 -5.3; 4788 -5.0; 5267 -5.9; 5793 -6.2; 6373 -8.9; 7010 -8.6; 7711 -7.1; 8482 -6.1; 9330 -5.9; 10263 -5.9; 11289 -5.9; 12418 -5.9; 13660 -5.9; 15026 -5.9; 16529 -5.9; 18182 -5.9; 20000 -5.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser HD 800 S GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 800 S ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.7dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 15 Hz   | 0.51 | 6.1 dB  |
| Peaking | 69 Hz   | 1.38 | 1.9 dB  |
| Peaking | 199 Hz  | 0.39 | -2.5 dB |
| Peaking | 2199 Hz | 0.6  | 3.1 dB  |
| Peaking | 6676 Hz | 3.76 | -4.2 dB |
| Peaking | 1497 Hz | 3.07 | 0.9 dB  |
| Peaking | 2004 Hz | 1.35 | -1.1 dB |
| Peaking | 2710 Hz | 1.08 | 0.8 dB  |
| Peaking | 3467 Hz | 6.73 | 0.9 dB  |
| Peaking | 4076 Hz | 4.37 | -1.2 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.9dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 4.2 dB  |
| Peaking | 62 Hz    | 1.41 | 1.4 dB  |
| Peaking | 125 Hz   | 1.41 | -1.5 dB |
| Peaking | 250 Hz   | 1.41 | -2.1 dB |
| Peaking | 500 Hz   | 1.41 | -1.0 dB |
| Peaking | 1000 Hz  | 1.41 | 0.7 dB  |
| Peaking | 2000 Hz  | 1.41 | 3.0 dB  |
| Peaking | 4000 Hz  | 1.41 | 1.3 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.8 dB |
| Peaking | 16000 Hz | 1.41 | 0.3 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20800%20S/Sennheiser%20HD%20800%20S.png)