# Sony MDR-Q68LW
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.5; 60 -0.6; 66 -1.9; 72 -3.1; 79 -4.2; 87 -5.0; 96 -5.6; 106 -6.1; 116 -6.3; 128 -6.5; 141 -6.8; 155 -6.8; 170 -6.8; 187 -6.8; 206 -6.7; 227 -6.7; 249 -6.4; 274 -6.0; 302 -5.8; 332 -5.6; 365 -5.4; 402 -5.3; 442 -5.2; 486 -5.1; 535 -4.9; 588 -4.9; 647 -5.0; 712 -5.1; 783 -5.2; 861 -5.5; 947 -5.9; 1042 -6.3; 1146 -6.5; 1261 -7.3; 1387 -8.4; 1526 -9.8; 1678 -10.7; 1846 -11.6; 2031 -11.5; 2234 -11.4; 2457 -11.3; 2703 -10.9; 2973 -9.5; 3270 -7.8; 3597 -7.8; 3957 -10.0; 4353 -9.0; 4788 -5.5; 5267 -2.0; 5793 -0.5; 6373 -1.4; 7010 -5.1; 7711 -7.8; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -7.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-Q68LW GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-Q68LW ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.2dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 35 Hz   | 0.79 | 7.0 dB  |
| Peaking | 703 Hz  | 0.97 | 2.0 dB  |
| Peaking | 1994 Hz | 1.48 | -5.2 dB |
| Peaking | 5079 Hz | 1    | -4.7 dB |
| Peaking | 5724 Hz | 2.65 | 11.5 dB |
| Peaking | 37 Hz   | 3.36 | -1.1 dB |
| Peaking | 60 Hz   | 2.98 | 2.3 dB  |
| Peaking | 128 Hz  | 1.19 | -1.2 dB |
| Peaking | 3443 Hz | 7.2  | 2.0 dB  |
| Peaking | 4068 Hz | 8    | -2.1 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.9dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.7 dB  |
| Peaking | 62 Hz    | 1.41 | 4.1 dB  |
| Peaking | 125 Hz   | 1.41 | -1.4 dB |
| Peaking | 250 Hz   | 1.41 | -0.1 dB |
| Peaking | 500 Hz   | 1.41 | 1.7 dB  |
| Peaking | 1000 Hz  | 1.41 | 1.6 dB  |
| Peaking | 2000 Hz  | 1.41 | -6.2 dB |
| Peaking | 4000 Hz  | 1.41 | 0.3 dB  |
| Peaking | 8000 Hz  | 1.41 | 1.8 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sony%20MDR-Q68LW/Sony%20MDR-Q68LW.png)