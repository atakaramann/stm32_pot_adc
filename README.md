## STM32 ADC Polling — Potentiometer & Temperature Sensor

**Board:** STM32 Nucleo F413ZH  
**IDE:** STM32CubeIDE  
**Library:** HAL  

### What it does
Reads potentiometer voltage and internal chip temperature via 
3-channel ADC polling. Real supply voltage (VDDA) is calculated 
using VREFINT calibration for accurate measurements.

### Key concepts
- 12-bit ADC resolution (0–4095)
- 3-channel sequential polling
- VREFINT calibration for accurate VDDA measurement
- Internal temperature sensor (V25 + AVG_SLOPE formula)
- Error handling via bool return and adc_error flag
