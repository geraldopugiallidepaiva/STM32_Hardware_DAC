# STM32_Hardware_DAC
 
This is a hardware implementation of a PWM-based DAC for the [NUCLEO-F103RB board](https://www.st.com/en/evaluation-tools/nucleo-f103rb.html) which do not feature a native DAC peripheral. As a result, it makes possible to generate analog voltage output capabilities to the development board, enabling its using in more advanced applications, only requiring a single pin for each analog output.

It was developed as an assignment for the subject Embedded Systems Programming at Universidade Federal de Minas Gerais - Prof. Ricardo de Oliveira Duarte - Department of Electronic Engineering.

The complete explanation and step-by-step is present in an [Application Note](https://github.com/geraldopugiallidepaiva/STM32_Hardware_DAC/blob/main/Application%20Note.pdf) and a simple [example](https://github.com/geraldopugiallidepaiva/STM32_Hardware_DAC/tree/main/example) is provided. The example, in particular, shows how to define the necessary parameter which controls the PWM duty cycle to vary the analog output at the output terminal of a low-pass filter circuit described in the Application Note. 

**Attention**

The circuit envolving an operational amplifier is generic, allowing any device to be used in the desing. However, it is advised for the user to check the datasheet for the specific device selected when implementing, specially to consider limitations due to power supply.
