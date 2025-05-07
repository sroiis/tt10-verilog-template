# Tiny FIFO Buffer

**Description:**  
This is a 16-depth FIFO buffer storing 6-bit values, designed using Verilog for Tiny Tapeout.  
It supports push (write), pop (read), and outputs full/empty flags and data output.

**Inputs:**
- `ui_in[0]`: Push (write enable)
- `ui_in[1]`: Pop (read enable)
- `ui_in[7:2]`: 6-bit input data

**Outputs:**
- `uo_out[0]`: Full flag
- `uo_out[1]`: Empty flag
- `uo_out[7:2]`: Data output
