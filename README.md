#Capturing DNS Traffic on Windows using Wireshark.
This is the easiest  guide on capturing DNS traffic using Wireshark on Windows. Wireshark is a valuable tool for diagnosing network issues, enhancing security, and optimising the performance of your network infrastructure. Wireshark is a widely used open-source network protocol analyzer. It allows users to capture and analyse the data travelling back and forth on a network in real-time. Wireshark is used for various purposes, including network troubleshooting, protocol development, and security analysis.

It is essential to understand the purpose of capturing traffic with DNS on Windows using Wireshark.

1. Wireshark could be used to detect unauthorised DNS requests on your Windows.

2. It could be helpful to diagnose and resolve DNS-related problems.

3. Analysing DNS traffic can help troubleshoot internet connectivity.

4. Wireshark could be helpful in DNS configurations and verifications.

What are the steps you need to take to install Wireshark on your host Windows successfully?

To install Wireshark, you can follow the steps below:
1. Visit the official Wireshark website via wireshark.org.

2. Click on the "Download" link on the website.
Choose the appropriate version for your Windows system (32-bit or 64-bit).

3. Once the download is complete, run the installer as an administrator.

4. Choose the components you want to install.

5. During installation, you may be required to install WinPcap. I agree to install it, as it is necessary for capturing network traffic.

6. Follow the basic instructions displayed on your screen. Tick the necessary options suitable for you to complete the installation.

7. After installation, launch Wireshark. It might require you to restart your PC automatically or manually; it all depends on your choice.

8. In the main Wireshark window, select the network interface that is connected to the network where you want to capture DNS traffic (you will have a series of options based on your connections, such as wireless Wi-Fi, Ethernet, etc.).

9. Click on the green "Start" button (a traffic light icon) to begin capturing network traffic.

10. When you start capturing, you will see TCP/UDP displayed. You can type "DNS" in the filter bar and press Enter. This will filter the captured traffic to display only DNS-related packets.

11. Wireshark would display DNS packets. You can analyse the details of each DNS request to see if it corresponds with your data on Windows.

12. When you feel satisfied with the captured data, you can click the red "Stop" icon at the top left corner to stop the capture.

13. You can save the captured traffic by clicking on the file at the top left corner of your window and selecting "Save as," then choosing a location and renaming your file. Save for future analysis.

The image attached to my caption is the result of my network capture on my host window.

You can also try this to see how it works.[Capturing DNS Traffic on Windows using Wireshark..docx](https://github.com/Adebhay1/Network-Analysis/files/14510668/Capturing.DNS.Traffic.on.Windows.using.Wireshark.docx)

You can watch the taached video link for a guide https://youtu.be/TfHDc9pzYNM?si=R9MYqaUnY6RTWSAW
