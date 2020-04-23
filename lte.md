[http://anisimoff.org/eng/lte_throughput.html](http://anisimoff.org/eng/lte_throughput.html)

[LTE freq bands](http://anisimoff.org/eng/lte_bands.html) ------ [5G bands](http://anisimoff.org/eng/5g/5g_spectrum.html)

[Code Rate from sharetechnote.com/html/Handbook](https://www.sharetechnote.com/html/Handbook_LTE_CodeRate.html)

## How to compute TBS

[https://ltebasics.wordpress.com/2014/11/17/transport-block-size-determination-in-lte/](https://ltebasics.wordpress.com/2014/11/17/transport-block-size-determination-in-lte/)

The MAC has to first decide on the modulation scheme that can be scheduled to the user and then check the physical resource grid for availability of the resource blocks. From this step the MAC can decide upon the modulation and coding scheme index (I_MCS)  and then decide upon the number of resource blocks (N_PRB), that can be allocated to the user. After this step the transport block size index (I_TBS) is derived from the look up table as specified in the LTE phy specification 36.213 sec 7.1.7.1 for downlink and sec 8.6.1 for uplink.

So after knowing the I_TBS and N_PRB, there shall be a table look up as specified in [LTE phy specification 36.213, section 7.1.7.2.1](https://www.etsi.org/deliver/etsi_ts/136200_136299/136213/12.03.00_60/ts_136213v120300p.pdf) , which will determine the transport block size for the current subframe for the user.

[MCS/TBS Determination from sharetechnote.com](https://www.sharetechnote.com/html/Handbook_LTE_BL_MCS_TBS.html)


## CQI definition in [3GPP TS 36.213](https://www.etsi.org/deliver/etsi_ts/136200_136299/136213/14.02.00_60/ts_136213v140200p.pdf) sec 7.2.3
The CQI indices and their interpretations are given in Table 7.2.3-1 for reporting CQI based on QPSK, 16QAM and 64QAM.<br> 
The CQI indices and their interpretations are given in Table 7.2.3-2 for reporting CQI based on QPSK, 16QAM, 64QAM and 256QAM.<br> 
The CQI indices and their interpretations are given in Table 7.2.3-3 for reporting CQI based on QPSK and 16QAM. <br>

5G SNR vs CQI curve is in [this paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6427249/pdf/sensors-19-01196.pdf) (see table 5 in [1]) <br>
LTE SINR vs CQI curve is in [this paper](https://jwcn-eurasipjournals.springeropen.com/articles/10.1186/s13638-015-0388-0/tables/1) (see Table 1 in [2]) <br>

[1] "A Novel Link-to-System Mapping Technique Based on Machine Learning for 5G/IoT Wireless Networks", Eunmi Chu et al, Sensors, 2015 <br>
[2] "Adaptive CSI and feedback estimation in LTE and beyond: a Gaussian process regression approach", Alessandro Chiumento et al, EURASIP Journal on Wireless Communications and Networking volume 2015, Article number: 168 (2015)
<br>

## Papers
[Inter-Cell Radio Frame Coordination Scheme Based
on Sliding Codebook for 5G TDD Systems, by Esswie et al](https://arxiv.org/pdf/1902.02980.pdf)

