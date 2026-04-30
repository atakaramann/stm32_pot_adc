STM32 ADC Voltage and Temperature Monitor
Board: STM32 Nucleo F413ZH
IDE: STM32CubeIDE
Library: HAL

What it does
Reads potentiometer, internal reference (VREFINT) and temperature sensor using ADC.  
Calculates real VDDA, converts ADC values to voltage and estimates temperature.

Key concepts
Multi-channel ADC conversion
VREFINT-based VDDA calculation
ADC to voltage conversion (12-bit resolution)
Internal temperature sensor usage
Polling-based ADC reading with HAL_ADC_PollForConversion()
Float calculations for physical values
