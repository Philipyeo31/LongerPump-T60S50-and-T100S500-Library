# LongerPump-T60S50-and-T100S500-Library
Simplifying control of RS485 versions of T60S50 and T100S500 PCB for LongerPump pumps

## How To Use
Currently there are only 2 fuctions working. To run, and to stop. 

The functions are as follows: 

`run(int address, int speed, float revolutions, bool direction)` 

- `address` is an integer, which can be set following the instruction manual for the pumps. 

- `speed` is an integer to set the RPM of the pump in resolutions of 0.1 e.g 40 RPM, is 400.

- `revolutions` is a float number to set the number of revolutions the pump turns for. 

  - If `revolutions` is set to 0, the pump will run indefinitely until the `stop(int address)` function is called.
  
- `direction` sets the direction, where `1` is clockwise and `0` is anti-clockwise

 

`stop(int address)`
- `address` is an integer, which can be set following the instruction manual for the pumps. 

<details><summary> ## Code Explanation </summary>
<p>

### I will work on these tomorrow!

</p>
</details>
