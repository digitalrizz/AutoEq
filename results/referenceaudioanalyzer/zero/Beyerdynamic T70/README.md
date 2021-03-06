# Beyerdynamic T70
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.5; 60 -0.6; 66 -1.0; 72 -1.5; 79 -1.9; 87 -2.2; 96 -2.6; 106 -2.9; 116 -3.2; 128 -3.5; 141 -3.7; 155 -3.7; 170 -3.4; 187 -3.0; 206 -2.7; 227 -2.8; 249 -3.9; 274 -5.9; 302 -8.1; 332 -9.8; 365 -10.7; 402 -10.9; 442 -10.3; 486 -9.1; 535 -8.1; 588 -7.9; 647 -7.7; 712 -7.5; 783 -7.2; 861 -7.0; 947 -6.8; 1042 -6.6; 1146 -6.3; 1261 -6.1; 1387 -6.0; 1526 -5.9; 1678 -5.6; 1846 -5.3; 2031 -5.6; 2234 -5.6; 2457 -4.5; 2703 -3.2; 2973 -3.6; 3270 -5.0; 3597 -6.4; 3957 -5.5; 4353 -3.3; 4788 -4.1; 5267 -5.7; 5793 -4.9; 6373 -6.1; 7010 -9.2; 7711 -13.2; 8482 -15.9; 9330 -16.6; 10263 -15.8; 11289 -14.3; 12418 -12.0; 13660 -8.9; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Beyerdynamic T70 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic T70 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 35 Hz    | 0.33 | 6.3 dB   |
| Peaking | 230 Hz   | 1.88 | 4.6 dB   |
| Peaking | 365 Hz   | 1.41 | -6.0 dB  |
| Peaking | 5822 Hz  | 0.6  | 5.8 dB   |
| Peaking | 9215 Hz  | 1.24 | -14.7 dB |
| Peaking | 2811 Hz  | 5.26 | 2.1 dB   |
| Peaking | 3711 Hz  | 4.32 | -2.6 dB  |
| Peaking | 4436 Hz  | 8.28 | 1.8 dB   |
| Peaking | 12191 Hz | 2.37 | -3.2 dB  |
| Peaking | 14229 Hz | 1.09 | 2.4 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.9dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.4 dB  |
| Peaking | 62 Hz    | 1.41 | 4.3 dB  |
| Peaking | 125 Hz   | 1.41 | 2.5 dB  |
| Peaking | 250 Hz   | 1.41 | 1.6 dB  |
| Peaking | 500 Hz   | 1.41 | -4.3 dB |
| Peaking | 1000 Hz  | 1.41 | 0.7 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.7 dB  |
| Peaking | 4000 Hz  | 1.41 | 4.7 dB  |
| Peaking | 8000 Hz  | 1.41 | -9.1 dB |
| Peaking | 16000 Hz | 1.41 | -0.9 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Beyerdynamic%20T70/Beyerdynamic%20T70.png)