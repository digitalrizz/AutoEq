# NuForce NE-600X
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -20.0; 23 -20.0; 25 -19.9; 28 -19.7; 31 -19.5; 34 -19.3; 37 -19.1; 41 -18.7; 45 -18.4; 49 -18.0; 54 -17.5; 60 -17.0; 66 -16.4; 72 -15.8; 79 -15.1; 87 -14.4; 96 -13.7; 106 -13.2; 116 -12.7; 128 -12.0; 141 -11.1; 155 -10.0; 170 -9.0; 187 -9.2; 206 -9.6; 227 -9.3; 249 -8.4; 274 -7.4; 302 -6.5; 332 -5.7; 365 -5.0; 402 -4.3; 442 -3.6; 486 -3.0; 535 -2.5; 588 -2.1; 647 -1.6; 712 -1.1; 783 -0.8; 861 -0.5; 947 -0.5; 1042 -0.5; 1146 -0.5; 1261 -0.7; 1387 -1.1; 1526 -1.7; 1678 -2.5; 1846 -3.5; 2031 -4.9; 2234 -7.1; 2457 -9.9; 2703 -12.0; 2973 -12.9; 3270 -12.8; 3597 -12.1; 3957 -11.8; 4353 -12.6; 4788 -13.2; 5267 -12.2; 5793 -8.6; 6373 -4.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -8.5; 10263 -6.6; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`NuForce NE-600X GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `NuForce NE-600X ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.2dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 34 Hz   | 0.26 | -11.1 dB |
| Peaking | 1624 Hz | 0.32 | 8.8 dB   |
| Peaking | 2946 Hz | 1.25 | -13.6 dB |
| Peaking | 4796 Hz | 3.44 | -7.2 dB  |
| Peaking | 18 Hz   | 0.75 | -3.4 dB  |
| Peaking | 171 Hz  | 3.46 | 1.4 dB   |
| Peaking | 224 Hz  | 3.29 | -1.6 dB  |
| Peaking | 6747 Hz | 5.52 | 5.6 dB   |
| Peaking | 7921 Hz | 1.06 | -1.8 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -14.5 dB |
| Peaking | 62 Hz    | 1.41 | -7.3 dB  |
| Peaking | 125 Hz   | 1.41 | -3.6 dB  |
| Peaking | 250 Hz   | 1.41 | -1.4 dB  |
| Peaking | 500 Hz   | 1.41 | 3.3 dB   |
| Peaking | 1000 Hz  | 1.41 | 6.9 dB   |
| Peaking | 2000 Hz  | 1.41 | 1.2 dB   |
| Peaking | 4000 Hz  | 1.41 | -8.5 dB  |
| Peaking | 8000 Hz  | 1.41 | 2.1 dB   |
| Peaking | 16000 Hz | 1.41 | -0.2 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/NuForce%20NE-600X/NuForce%20NE-600X.png)