# EBAZ4205 pinout

## By pin

### MIO

| Pin | Signal       | Connection      |
| --- | ------------ | --------------- |
| E6  | PS_MIO0_500  | NAND_CE#        |
| A7  | PS_MIO1_500  | NC              |
| B8  | PS_MIO2_500  | NAND_ALE        |
| D6  | PS_MIO3_500  | NAND_WE#        |
| B7  | PS_MIO4_500  | NAND_IO2        |
| A6  | PS_MIO5_500  | NAND_IO0        |
| A5  | PS_MIO6_500  | NAND_IO1        |
| D8  | PS_MIO7_500  | NAND_CLE        |
| D5  | PS_MIO8_500  | NAND_RD#        |
| B5  | PS_MIO9_500  | NAND_IO4        |
| E9  | PS_MIO10_500 | NAND_IO5        |
| C6  | PS_MIO11_500 | NAND_IO6        |
| D9  | PS_MIO12_500 | NAND_IO7        |
| E8  | PS_MIO13_500 | NAND_IO3        |
| C5  | PS_MIO14_500 | NAND_RY_BY#     |
| C8  | PS_MIO15_500 | NC              |
| A19 | PS_MIO16_501 | PL_PS_CLK2 (?)  |
| E14 | PS_MIO17_501 | NC              |
| B18 | PS_MIO18_501 | PL_PS_CLK1 (?)  |
| D10 | PS_MIO19_501 | NC              |
| A17 | PS_MIO20_501 | SW2             |
| F14 | PS_MIO21_501 | NC              |
| B17 | PS_MIO22_501 | NC              |
| D11 | PS_MIO23_501 | NC              |
| A16 | PS_MIO24_501 | UART_TX         |
| F15 | PS_MIO25_501 | UART_RX         |
| A15 | PS_MIO26_501 | RTC_SCL         |
| D13 | PS_MIO27_501 | RTC_SDA         |
| C16 | PS_MIO28_501 | STRAPPING_08    |
| C13 | PS_MIO29_501 | STRAPPING_05    |
| C15 | PS_MIO30_501 | STRAPPING_06    |
| E16 | PS_MIO31_501 | STRAPPING_12    |
| A14 | PS_MIO32_501 | SW3             |
| D15 | PS_MIO33_501 | NC              |
| A12 | PS_MIO34_501 | SD_CD#          |
| F12 | PS_MIO35_501 | 20K_PULL_UP     |
| A11 | PS_MIO36_501 | NC              |
| A10 | PS_MIO37_501 | NC              |
| E13 | PS_MIO38_501 | STRAPPING_11    |
| C18 | PS_MIO39_501 | STRAPPING_09    |
| D14 | PS_MIO40_501 | SD_CLK          |
| C17 | PS_MIO41_501 | SD_CMD          |
| E12 | PS_MIO42_501 | SD_DAT0         |
| A9  | PS_MIO43_501 | SD_DAT1         |
| F13 | PS_MIO44_501 | SD_DAT2         |
| B15 | PS_MIO45_501 | SD_DAT3         |
| D16 | PS_MIO46_501 | STRAPPING_10    |
| B14 | PS_MIO47_501 | STRAPPING_03    |
| B12 | PS_MIO48_501 | STRAPPING_01    |
| C12 | PS_MIO49_501 | STRAPPING_04    |
| B13 | PS_MIO50_501 | STRAPPING_02    |
| B9  | PS_MIO51_501 | NC              |
| C10 | PS_MIO52_501 | NC              |
| C11 | PS_MIO53_501 | NC              |

### PL I/Os

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| T10 | IO_L1N_T0_34            | NC                  |
| T11 | IO_L1P_T0_34            | NC                  |
| U12 | IO_L2N_T0_34            | ISO_OUT_1           |
| T12 | IO_L2P_T0_34            | NC                  |
| V13 | IO_L3N_T0_DQS_34        | ISO_IN_1            |
| U13 | IO_L3P_T0_DQS_PUDC_B_34 | PUDC_B (pull-down)  |
| W13 | IO_L4N_T0_34            | LED_GREEN           |
| V12 | IO_L4P_T0_34            | ISO_OUT_2           |
| T15 | IO_L5N_T0_34            | NC                  |
| T14 | IO_L5P_T0_34            | NC                  |
| R14 | IO_L6N_T0_VREF_34       | NC                  |
| P14 | IO_L6P_T0_34            | NC                  |
| Y17 | IO_L7N_T1_34            | RMII_RXD3           |
| Y16 | IO_L7P_T1_34            | RMII_RXD0           |
| Y14 | IO_L8N_T1_34            | MDIO                |
| W14 | IO_L8P_T1_34            | LED_RED             |
| U17 | IO_L9N_T1_DQS_34        | NC                  |
| T16 | IO_L9P_T1_DQS_34        | NC                  |
| W15 | IO_L10N_T1_34           | MDC                 |
| V15 | IO_L10P_T1_34           | ISO_IN_2            |
| U15 | IO_L11N_T1_SRCC_34      | RMII_TXCLK          |
| U14 | IO_L11P_T1_SRCC_34      | RMII_RXCLK          |
| U19 | IO_L12N_T1_MRCC_34      | DATA3_20            |
| U18 | IO_L12P_T1_MRCC_34      | CLK_50M_PHY         |
| P19 | IO_L13N_T2_MRCC_34      | DATA3_15            |
| N18 | IO_L13P_T2_MRCC_34      | CLK_??M_FPGA        |
| P20 | IO_L14N_T2_SRCC_34      | DATA3_11            |
| N20 | IO_L14P_T2_SRCC_34      | DATA3_6             |
| U20 | IO_L15N_T2_DQS_34       | DATA3_17            |
| T20 | IO_L15P_T2_DQS_34       | DATA3_16            |
| W20 | IO_L16N_T2_34           | ACOI_PIN2           |
| V20 | IO_L16P_T2_34           | DATA3_19            |
| Y19 | IO_L17N_T2_34           | RMII_TXD3           |
| Y18 | IO_L17P_T2_34           | RMII_TXD1           |
| W16 | IO_L18N_T2_34           | RMII_RXDV           |
| V16 | IO_L18P_T2_34           | RMII_RXD1           |
| R17 | IO_L19N_T3_VREF_34      | NC                  |
| R16 | IO_L19P_T3_34           | NC                  |
| R18 | IO_L20N_T3_34           | DATA3_13            |
| T17 | IO_L20P_T3_34           | NC                  |
| V18 | IO_L21N_T3_DQS_34       | RMII_TXD2           |
| V17 | IO_L21P_T3_DQS_34       | RMII_RXD2           |
| W19 | IO_L22N_T3_34           | RMII_TXEN           |
| W18 | IO_L22P_T3_34           | RMII_TXD0           |
| P18 | IO_L23N_T3_34           | DATA3_7             |
| N17 | IO_L23P_T3_34           | DATA3_9             |
| P16 | IO_L24N_T3_34           | NC                  |
| P15 | IO_L24P_T3_34           | NC                  |
| R19 | IO_0_34                 | DATA3_14            |
| T19 | IO_25_34                | DATA3_18            |
| B20 | IO_L1N_T0_AD0N_35       | DATA1_8             |
| C20 | IO_L1P_T0_AD0P_35       | DATA1_9             |
| A20 | IO_L2N_T0_AD8N_35       | DATA1_5             |
| B19 | IO_L2P_T0_AD8P_35       | DATA1_7             |
| D18 | IO_L3N_T0_DQS_AD1N_35   | DATA1_14            |
| E17 | IO_L3P_T0_DQS_AD1P_35   | NC                  |
| D20 | IO_L4N_T0_35            | DATA1_13            |
| D19 | IO_L4P_T0_35            | DATA1_16            |
| E19 | IO_L5N_T0_AD9N_35       | DATA1_18            |
| E18 | IO_L5P_T0_AD9P_35       | NC                  |
| F17 | IO_L6N_T0_VREF_35       | NC                  |
| F16 | IO_L6P_T0_35            | NC                  |
| M20 | IO_L7N_T1_AD2N_35       | DATA2_19            |
| M19 | IO_L7P_T1_AD2P_35       | DATA3_5             |
| M18 | IO_L8N_T1_AD10N_35      | DATA2_17            |
| M17 | IO_L8P_T1_AD10P_35      | DATA3_8             |
| L20 | IO_L9N_T1_DQS_AD3N_35   | DATA2_18            |
| L19 | IO_L9P_T1_DQS_AD3P_35   | DATA2_16            |
| J19 | IO_L10N_T1_AD11N_35     | DATA2_9             |
| K19 | IO_L10P_T1_AD11P_35     | DATA2_13            |
| L17 | IO_L11N_T1_SRCC_35      | DATA2_20            |
| L16 | IO_L11P_T1_SRCC_35      | DATA2_15            |
| K18 | IO_L12N_T1_MRCC_35      | DATA2_11            |
| K17 | IO_L12P_T1_MRCC_35      | DATA1_20            |
| H17 | IO_L13N_T2_MRCC_35      | DATA1_11            |
| H16 | IO_L13P_T2_MRCC_35      | DATA1_6             |
| H18 | IO_L14N_T2_AD4N_SRCC_35 | DATA1_15            |
| J18 | IO_L14P_T2_AD4P_SRCC_35 | DATA2_6             |
| F20 | IO_L15N_T2_DQS_AD12N_35 | DATA1_17            |
| F19 | IO_L15P_T2_DQS_AD12P_35 | DATA1_19            |
| G18 | IO_L16N_T2_35           | NC                  |
| G17 | IO_L16P_T2_35           | NC                  |
| H20 | IO_L17N_T2_AD5N_35      | DATA2_8             |
| J20 | IO_L17P_T2_AD5P_35      | DATA2_14            |
| G20 | IO_L18N_T2_AD13N_35     | DATA2_5             |
| G19 | IO_L18P_T2_AD13P_35     | DATA2_7             |
| G15 | IO_L19N_T3_VREF_35      | NC                  |
| H15 | IO_L19P_T3_35           | NC                  |
| J14 | IO_L20N_T3_AD6N_35      | NC                  |
| K14 | IO_L20P_T3_AD6P_35      | NC                  |
| N16 | IO_L21N_T3_DQS_AD14N_35 | PL_PS_CLK2 (?)      |
| N15 | IO_L21P_T3_DQS_AD14P_35 | NC                  |
| L15 | IO_L22N_T3_AD7N_35      | NC                  |
| L14 | IO_L22P_T3_AD7P_35      | PL_PS_CLK1 (?)      |
| M15 | IO_L23N_T3_35           | NC                  |
| M14 | IO_L23P_T3_35           | NC                  |
| J16 | IO_L24N_T3_AD15N_35     | NC                  |
| K16 | IO_L24P_T3_AD15P_35     | NC                  |
| G14 | IO_0_35                 | NC                  |
| J15 | IO_25_35                | NC                  |

## By Group

### MIO

#### NAND

| Pin | Signal       | Connection      |
| --- | ------------ | --------------- |
| E6  | PS_MIO0_500  | NAND_CE#        |
| D6  | PS_MIO3_500  | NAND_WE#        |
| D5  | PS_MIO8_500  | NAND_RD#        |
| B8  | PS_MIO2_500  | NAND_ALE        |
| D8  | PS_MIO7_500  | NAND_CLE        |
| C5  | PS_MIO14_500 | NAND_RY_BY#     |
| A6  | PS_MIO5_500  | NAND_IO0        |
| A5  | PS_MIO6_500  | NAND_IO1        |
| B7  | PS_MIO4_500  | NAND_IO2        |
| E8  | PS_MIO13_500 | NAND_IO3        |
| B5  | PS_MIO9_500  | NAND_IO4        |
| E9  | PS_MIO10_500 | NAND_IO5        |
| C6  | PS_MIO11_500 | NAND_IO6        |
| D9  | PS_MIO12_500 | NAND_IO7        |

#### MicroSD

| Pin | Signal       | Connection      |
| --- | ------------ | --------------- |
| D14 | PS_MIO40_501 | SD_CLK          |
| C17 | PS_MIO41_501 | SD_CMD          |
| E12 | PS_MIO42_501 | SD_DAT0         |
| A9  | PS_MIO43_501 | SD_DAT1         |
| F13 | PS_MIO44_501 | SD_DAT2         |
| B15 | PS_MIO45_501 | SD_DAT3         |
| A12 | PS_MIO34_501 | SD_CD#          |

#### External PS/PL interconnection

| Pin | Signal       | Connection      |
| --- | ------------ | --------------- |
| B18 | PS_MIO18_501 | PL_PS_CLK1 (?)  |
| A19 | PS_MIO16_501 | PL_PS_CLK2 (?)  |

#### Switch

| Pin | Signal       | Connection      |
| --- | ------------ | --------------- |
| A17 | PS_MIO20_501 | SW2             |
| A14 | PS_MIO32_501 | SW3             |

#### UART

| Pin | Signal       | Connection      |
| --- | ------------ | --------------- |
| A16 | PS_MIO24_501 | UART_TX         |
| F15 | PS_MIO25_501 | UART_RX         |

#### RTC

| Pin | Signal       | Connection      |
| --- | ------------ | --------------- |
| A15 | PS_MIO26_501 | RTC_SCL         |
| D13 | PS_MIO27_501 | RTC_SDA         |

#### Strappings

| Pin | Signal       | Connection      |
| --- | ------------ | --------------- |
| C16 | PS_MIO28_501 | STRAPPING_08    |
| C13 | PS_MIO29_501 | STRAPPING_05    |
| C15 | PS_MIO30_501 | STRAPPING_06    |
| E16 | PS_MIO31_501 | STRAPPING_12    |
| F12 | PS_MIO35_501 | 20K_PULL_UP     |
| E13 | PS_MIO38_501 | STRAPPING_11    |
| C18 | PS_MIO39_501 | STRAPPING_09    |
| D16 | PS_MIO46_501 | STRAPPING_10    |
| B14 | PS_MIO47_501 | STRAPPING_03    |
| B12 | PS_MIO48_501 | STRAPPING_01    |
| C12 | PS_MIO49_501 | STRAPPING_04    |
| B13 | PS_MIO50_501 | STRAPPING_02    |

### PL I/Os

#### Ethernet

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| W15 | IO_L10N_T1_34           | MDC                 |
| Y14 | IO_L8N_T1_34            | MDIO                |
| U14 | IO_L11P_T1_SRCC_34      | RMII_RXCLK          |
| W16 | IO_L18N_T2_34           | RMII_RXDV           |
| Y16 | IO_L7P_T1_34            | RMII_RXD0           |
| V16 | IO_L18P_T2_34           | RMII_RXD1           |
| V17 | IO_L21P_T3_DQS_34       | RMII_RXD2           |
| Y17 | IO_L7N_T1_34            | RMII_RXD3           |
| U15 | IO_L11N_T1_SRCC_34      | RMII_TXCLK          |
| W19 | IO_L22N_T3_34           | RMII_TXEN           |
| W18 | IO_L22P_T3_34           | RMII_TXD0           |
| Y18 | IO_L17P_T2_34           | RMII_TXD1           |
| V18 | IO_L21N_T3_DQS_34       | RMII_TXD2           |
| Y19 | IO_L17N_T2_34           | RMII_TXD3           |

#### LEDs

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| W13 | IO_L4N_T0_34            | LED_GREEN           |
| W14 | IO_L8P_T1_34            | LED_RED             |

#### Isolated I/Os

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| U12 | IO_L2N_T0_34            | ISO_OUT_1           |
| V13 | IO_L3N_T0_DQS_34        | ISO_IN_1            |
| V12 | IO_L4P_T0_34            | ISO_OUT_2           |
| V15 | IO_L10P_T1_34           | ISO_IN_2            |

#### Clocks

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| U18 | IO_L12P_T1_MRCC_34      | CLK_50M_PHY         |
| N18 | IO_L13P_T2_MRCC_34      | CLK_??M_FPGA        |

#### Data Port 1

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| A20 | IO_L2N_T0_AD8N_35       | DATA1_5             |
| B19 | IO_L2P_T0_AD8P_35       | DATA1_7             |
| H16 | IO_L13P_T2_MRCC_35      | DATA1_6             |
| B20 | IO_L1N_T0_AD0N_35       | DATA1_8             |
| C20 | IO_L1P_T0_AD0P_35       | DATA1_9             |
| H17 | IO_L13N_T2_MRCC_35      | DATA1_11            |
| D20 | IO_L4N_T0_35            | DATA1_13            |
| D18 | IO_L3N_T0_DQS_AD1N_35   | DATA1_14            |
| H18 | IO_L14N_T2_AD4N_SRCC_35 | DATA1_15            |
| D19 | IO_L4P_T0_35            | DATA1_16            |
| F20 | IO_L15N_T2_DQS_AD12N_35 | DATA1_17            |
| E19 | IO_L5N_T0_AD9N_35       | DATA1_18            |
| F19 | IO_L15P_T2_DQS_AD12P_35 | DATA1_19            |
| K17 | IO_L12P_T1_MRCC_35      | DATA1_20            |


#### Data Port 2

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| G20 | IO_L18N_T2_AD13N_35     | DATA2_5             |
| J18 | IO_L14P_T2_AD4P_SRCC_35 | DATA2_6             |
| G19 | IO_L18P_T2_AD13P_35     | DATA2_7             |
| H20 | IO_L17N_T2_AD5N_35      | DATA2_8             |
| J19 | IO_L10N_T1_AD11N_35     | DATA2_9             |
| K18 | IO_L12N_T1_MRCC_35      | DATA2_11            |
| K19 | IO_L10P_T1_AD11P_35     | DATA2_13            |
| J20 | IO_L17P_T2_AD5P_35      | DATA2_14            |
| L16 | IO_L11P_T1_SRCC_35      | DATA2_15            |
| L19 | IO_L9P_T1_DQS_AD3P_35   | DATA2_16            |
| M18 | IO_L8N_T1_AD10N_35      | DATA2_17            |
| L20 | IO_L9N_T1_DQS_AD3N_35   | DATA2_18            |
| M20 | IO_L7N_T1_AD2N_35       | DATA2_19            |
| L17 | IO_L11N_T1_SRCC_35      | DATA2_20            |


#### Data Port 3

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| M19 | IO_L7P_T1_AD2P_35       | DATA3_5             |
| N20 | IO_L14P_T2_SRCC_34      | DATA3_6             |
| P18 | IO_L23N_T3_34           | DATA3_7             |
| M17 | IO_L8P_T1_AD10P_35      | DATA3_8             |
| N17 | IO_L23P_T3_34           | DATA3_9             |
| P20 | IO_L14N_T2_SRCC_34      | DATA3_11            |
| R18 | IO_L20N_T3_34           | DATA3_13            |
| R19 | IO_0_34                 | DATA3_14            |
| P19 | IO_L13N_T2_MRCC_34      | DATA3_15            |
| T20 | IO_L15P_T2_DQS_34       | DATA3_16            |
| U20 | IO_L15N_T2_DQS_34       | DATA3_17            |
| V20 | IO_L16P_T2_34           | DATA3_19            |
| T19 | IO_25_34                | DATA3_18            |
| U19 | IO_L12N_T1_MRCC_34      | DATA3_20            |

#### External PS/PL interconnection

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| N16 | IO_L21N_T3_DQS_AD14N_35 | PL_PS_CLK2 (?)      |
| L14 | IO_L22P_T3_AD7P_35      | PL_PS_CLK1 (?)      |

#### Misc

| Pin | Signal                  | Connection          |
| --- | ----------------------- | ------------------- |
| U13 | IO_L3P_T0_DQS_PUDC_B_34 | PUDC_B (pull-down)  |
| W20 | IO_L16N_T2_34           | ACOI_PIN2           |