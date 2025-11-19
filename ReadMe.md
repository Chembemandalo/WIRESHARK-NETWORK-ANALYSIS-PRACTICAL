This repository contains the required files for the ICT414 Information Security Practical, focusing on network traffic analysis using Wireshark.

Files Included:

    ict414_capture.pcapng: The raw Wireshark capture file.

    report_Daniel Chembe Mandalo.pdf: The formal analysis report detailing the HTTP transaction.

     This file, explaining the steps followed.

Steps Followed for Traffic Capture and Analysis
  1. Preparation: Started Wireshark on the appropriate network interface ( wlan0).
   
 
  2.   Traffic Capture: Started the live capture function in Wireshark.

  
  3.  Website Access: Opened a web browser first cleares my brower cache then  navigated to the target URL: www.rocktv.app.

  4.  Capture Stoppage: Stopped the Wireshark capture after approximately two minutes.

 5.   Filtering: Applied the following display filters to isolate the relevant traffic:

        http: To display all HTTP protocol packets.

        ip.addr == 192.168.114.249: to  focus specifically on traffic to and from my client machine 

 6.   Identification: Identified the required HTTP GET request and its corresponding 200 OK response.

  7. Analysis: Extracted the client IP, server IP, requested URL, and response code to complete the analysis report.
x

