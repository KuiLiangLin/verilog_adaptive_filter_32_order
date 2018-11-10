# adaptive-filter_32-order

<em><a href="https://github.com/KuiLiangLin/verilog_adaptive_filter_32_order/">View adaptive filter 32 order on GitHub</a></em>. 

<hr>

<h4> This FPGA project is a 32 orders adaptive filter with s2p and p2s to communicate with Renesas RX210 MCU. </h4>

<ol>

<li>Waveform overview : Input : mosi ; Output : miso 
    <img src="https://raw.githubusercontent.com/KuiLiangLin/verilog_adaptive_filter_32_order/master/Waveform_Overview.JPG" height="100%" width="100%">
</li>

<li>Waveform algorithm top : Use basic FIFO structure to store 32 input dates and do 32 orders adaptive filter.
    <img src="https://raw.githubusercontent.com/KuiLiangLin/verilog_adaptive_filter_32_order/master/Waveform_algorithm_top.JPG" height="100%" width="100%" >
</li>

<li>Waveform s2p : Convert serial data input (miso) to Parallel data output (ad_1, ad_2).
    <img src="https://raw.githubusercontent.com/KuiLiangLin/verilog_adaptive_filter_32_order/master/Waveform_s2p.JPG" height="100%" width="100%" >
</li>

<li>p2s : Convert parallel data input (in_p2s) to Serial data output (mosi).
    <img src="https://raw.githubusercontent.com/KuiLiangLin/verilog_adaptive_filter_32_order/master/Waveform_p2s.JPG" height="100%" width="100%" >
</li>

<li>Waveform adaptive filter :
    <img src="https://raw.githubusercontent.com/KuiLiangLin/verilog_adaptive_filter_32_order/master/Waveform_adaptive_filter.JPG" height="100%" width="100%" >
</li>

<li>Algorithm structure is based on this picture:
    <img src="https://camo.githubusercontent.com/0917e9d4aef78e9ce5e738c56ea0a19057ac2be4/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f662f66362f416461707469766546696c7465725f432e706e67" height="100%" width="100%" >
</li>
</ol>

<hr>
<h3> END </h3>
<ul><li> Codes are <em><a href="https://github.com/KuiLiangLin/verilog_adaptive_filter_32_order/">Here</a></em>. </li></ul>
<ul><li> You can return <em><a href="https://kuilianglin.github.io/Welcome/">My Main Page</a></em>. </li></ul>



