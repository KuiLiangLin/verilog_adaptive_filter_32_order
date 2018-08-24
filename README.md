# adaptive-filter_32-order

This FPGA project is a 32 orders adaptive filter with s2p and p2s to communicate with Renesas RX210 MCU.

1. Waveform overview : Input : mosi ; Output : miso

   ![image](https://github.com/KuiLiangLin/verilog_adaptive_filter_32_order/blob/master/Waveform_Overview.JPG)

2. Waveform algorithm top : Use basic FIFO structure to store 32 input dates and do 32 orders adaptive filter.
   
   ![image](https://github.com/KuiLiangLin/verilog_adaptive_filter_32_order/blob/master/Waveform_algorithm_top.JPG)

3. Waveform s2p : Convert serial data input (miso) to Parallel data output (ad_1, ad_2).

   ![image](https://github.com/KuiLiangLin/verilog_adaptive_filter_32_order/blob/master/Waveform_s2p.JPG)

4. Waveform p2s : Convert parallel data input (in_p2s) to Serial data output (mosi).

   ![image](https://github.com/KuiLiangLin/verilog_adaptive_filter_32_order/blob/master/Waveform_p2s.JPG)

5. Waveform adaptive filter :

   ![image](https://github.com/KuiLiangLin/verilog_adaptive_filter_32_order/blob/master/Waveform_adaptive_filter.JPG)

   Algorithm structure is based on this picture:
   
   ![image](https://upload.wikimedia.org/wikipedia/commons/f/f6/AdaptiveFilter_C.png)






