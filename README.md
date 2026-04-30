## STM32 ADC Voltage and Temperature Monitor

**Board:** STM32 Nucleo F413ZH  
**IDE:** STM32CubeIDE  
**Library:** HAL  

### What it does
Reads potentiometer, VREFINT and internal temperature sensor via ADC and calculates voltage and temperature values.

### Key concepts
- Multi-channel ADC conversion
- VREFINT-based VDDA calculation
- 12-bit ADC to voltage conversion
- Internal temperature sensor usage
- HAL_ADC_PollForConversion() based reading
- Float-based calculations
