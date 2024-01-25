<h1>Active Directory Home Lab</h1>

 ### [Writeup](https://TBD)

<h2>Description</h2>
Welcome to the Active Directory Lab Setup Guide with pfSense on ESXi, featuring two Windows 10 hosts. This comprehensive guide is designed for learning purposes, providing a step-by-step walkthrough to establish a baseline Active Directory environment in an ESXi virtualization platform. The inclusion of pfSense enhances the security of the lab, creating a segmented network to shield your home network from potential malicious activities.

In this guide, we'll cover the installation and configuration of pfSense as a DHCP server, setting up Windows Server 2022 as the foundation for Active Directory, and deploying two Windows 10 hosts to interact with the AD domain. Each step is meticulously detailed, ensuring a smooth and educational experience in building and managing your Active Directory lab environment.

Feel free to follow along and explore the world of network administration, cybersecurity, and virtualization. Let's dive into the exciting realm of Active Directory and enhance our skills together!
<br />



<h2>Requirements for Active Directory Setup with pfSense on ESXi</h2>
  <ol>
    <li>
      <strong>ESXi Installation:</strong>
      <p>ESXi installed on a host machine.</p>
    </li>

    <li>
      <strong>Remote Console:</strong>
      <p>Download and install VMRC for better remote console access to ESXi VMs.</p>
    </li>

    <li>
      <strong>Firewall Solution:</strong>
      <p>pfSense: Download the pfSense ISO from the pfSense website.</p>
    </li>

    <li>
      <strong>Operating Systems:</strong>
      <p>
        <ul>
          <li>Windows Server 2022: Download the 64-bit ISO from the <a
              href="https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022">Microsoft Evaluation Center</a>.</li>
          <li>Windows 10: Download the 64-bit ISO from the <a
              href="https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise">Microsoft Evaluation
              Center</a>.</li>
        </ul>
      </p>
    </li>

    <li>
      <strong>Hardware Resources:</strong>
      <p>
        <ul>
          <li>RAM: 16GB to 32GB (more than 32GB is ideal).</li>
          <li>Disk Space: 500GB of free disk space for lab setup.</li>
        </ul>
      </p>
    </li>

    <li>
      <strong>Function Keys Consideration:</strong>
      <p>Be aware of potential issues with function keys (e.g., function keys, F11, etc.). Hold the function (fn) key if
        problems arise.</p>
    </li>
  </ol>

</body>

</html>


<h2>Program walk-through:</h2>

<p align="center">
Active Directory HomeLab: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="TBD"/>
<br />
<br />
TBD:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="TBD"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
