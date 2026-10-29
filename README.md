<div align="center">

**English** · [Türkçe](README.tr.md)

<img src="assets/neofetch.svg" width="100%" alt="neofetch: berat@github" />

</div>

<br>

## About me

- 🧊 Build **3D models from photos** (photogrammetry) and clean them up in **Blender**: mesh editing, UV mapping, optimisation
- 📱 Built an **augmented-reality restaurant menu** in Unity: point your phone at the menu and the dish appears in 3D
- 🛡️ Learning **cybersecurity** hands-on through TryHackMe: networking fundamentals, Linux/Windows terminals, Nmap, Wireshark, Metasploit
- 🧭 Studied **human–computer interaction**: designing UI/UX against established usability standards, prototyping in **Figma**
- 🧑‍💻 Write **C, C++ and C#**, know my way around **SQL**, and build for the web with React, HTML, CSS and JavaScript

<br>

## Tech stack

**3D & AR**<br>
<img src="https://skillicons.dev/icons?i=blender,unity&perline=8" alt="3D and AR" />
&nbsp;![Vuforia](https://img.shields.io/badge/Vuforia-AR-0F9D58?style=for-the-badge)
![RealityScan](https://img.shields.io/badge/RealityScan-Photogrammetry-black?style=for-the-badge)

**Security & systems**<br>
<img src="https://skillicons.dev/icons?i=linux,powershell,git&perline=8" alt="Systems" />
&nbsp;![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596D1?style=for-the-badge&logo=metasploit&logoColor=white)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)

**Languages**<br>
<img src="https://skillicons.dev/icons?i=c,cpp,cs,mysql&perline=8" alt="Languages" />

**Web**<br>
<img src="https://skillicons.dev/icons?i=react,html,css,js,figma&perline=8" alt="Web" />

<br>

## Cybersecurity: TryHackMe

<div align="center">

**Top 9% globally** · **60 rooms completed** · **6 badges** · **1,183 activity events in the last year**

</div>

<table align="center">
  <tr>
    <td align="center"><img src="assets/thm-blue.gif" width="150" alt="Blue badge" /><br><sub><b>Blue</b><br>Windows via EternalBlue</sub></td>
    <td align="center"><img src="assets/thm-metasploitable.gif" width="150" alt="Metasploitable badge" /><br><sub><b>Metasploitable</b><br>Using Metasploit</sub></td>
    <td align="center"><img src="assets/thm-networking-nerd.gif" width="150" alt="Networking Nerd badge" /><br><sub><b>Networking Nerd</b><br>Network Fundamentals</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/thm-cat-linux.gif" width="150" alt="cat linux.txt badge" /><br><sub><b>cat linux.txt</b><br>Linux competence</sub></td>
    <td align="center"><img src="assets/thm-webbed.gif" width="150" alt="Webbed badge" /><br><sub><b>Webbed</b><br>How the web works</sub></td>
    <td align="center"><img src="assets/thm-world-wide-web.gif" width="150" alt="World Wide Web badge" /><br><sub><b>World Wide Web</b><br>How The Web Works</sub></td>
  </tr>
</table>

<details>
<summary><b>Completed rooms (60)</b></summary>
<br>

| Area | Rooms |
| --- | --- |
| **Offensive security & tools** (12) | Nmap · Wireshark · Tcpdump · John the Ripper · Metasploit (3 rooms) · Blue · Moniker Link · Become a Hacker · Offensive Security · Web Applications |
| **Networking** (11) | DNS in Detail · OSI Model · Packets & Frames · Intro to LAN · HTTP in Detail · Networking Core · + 5 more networking rooms |
| **Windows & Active Directory** (8) | Windows Basics · Windows CLI · PowerShell · Active Directory · + 4 more Windows rooms |
| **Linux** (5) | Linux CLI Basics · Linux Shells · + 3 Linux fundamentals rooms |
| **Cryptography** (5) | Hashing Basics · Data Encoding · Public-key cryptography · Cryptography (2 rooms) |
| **Defensive security** (5) | The CIA Triad · Search Skills · Defensive Security · Careers in Cyber · + 1 more |
| **Web & programming** (7) | How websites work · Putting it all together · JavaScript (2 rooms) · Python · Database SQL · + 1 more |
| **Computing fundamentals** (7) | Computer Types · Inside a Computer · Client-Server · Operating Systems (2 rooms) · Virtualisation · Cloud Computing |

</details>

<br>

## Featured: AR Restaurant Menu

Scan a QR code on the menu with your phone and the dish shows up in 3D on the table, so you see the portion and presentation before you order. Every dish is a real plate photographed and rebuilt with photogrammetry, cleaned in Blender, and optimised for mobile.

<table align="center">
  <tr>
    <td align="center"><img src="assets/turntable-pirzola.gif" width="220" alt="Pork chop 3D model" /><br><sub>Pork chop &amp; fries</sub></td>
    <td align="center"><img src="assets/turntable-makarna.gif" width="220" alt="Pasta 3D model" /><br><sub>Pasta</sub></td>
    <td align="center"><img src="assets/turntable-tost.gif" width="220" alt="Toasted sandwich 3D model" /><br><sub>Toasted sandwich</sub></td>
  </tr>
</table>

**Unity · Vuforia · C# · Blender · RealityScan · Figma**

<details>
<summary><b>How I built it</b></summary>
<br>

1. **Capture:** about 100 photos per dish, shot around the plate from several heights.
2. **Reconstruct:** compared Kiri Engine and RealityScan on the same dish. RealityScan gave more detail, so every final model uses it.
3. **Clean up in Blender:** removed the table and stray geometry, repaired broken mesh regions, fixed UV problems.
4. **Optimise for mobile:** cut models from ~3M to ~50K polygons with Decimate and textures from 4K to 2K, which fixed stuttering on Android.
5. **Track the marker:** a Python-generated QR code as a Vuforia image target, rated 5/5 for detectability.
6. **Design the UI:** in Figma, then rebuilt it in Unity with category tabs and next/previous navigation.

</details>

<br>

## 3D work: backpacks from photos

I turned real backpacks into lightweight 3D models (13 designs so far). Photogrammetry rarely comes out clean, so a big part of the work was fixing broken regions in Blender: manual **mesh editing**, re-projecting **UV maps** from the good areas onto the bad ones, and decimating the result so it stays light.

<table align="center">
  <tr>
    <td align="center"><img src="assets/turntable-red.gif" width="220" alt="Red backpack 3D model" /></td>
    <td align="center"><img src="assets/turntable-heart.gif" width="220" alt="Heart-print backpack 3D model" /></td>
    <td align="center"><img src="assets/turntable-teal.gif" width="220" alt="Teal backpack 3D model" /></td>
  </tr>
</table>

<br>

## Skills at a glance

| Area | What I do |
| --- | --- |
| **3D** | Photogrammetry, mesh cleanup, UV mapping, polygon and texture optimisation in Blender |
| **AR** | Marker-based AR with Unity + Vuforia, mobile performance tuning |
| **Security** | TryHackMe rooms, networking basics, Nmap, Wireshark, Metasploit, Linux & Windows command line |
| **UI / UX** | Interface design in Figma, usability and HCI standards, design-to-code handoff |
| **Web** | React, HTML, CSS, JavaScript |

<br>

## Get in touch

<div align="center">

<a href="https://www.linkedin.com/in/berat-%C5%9Fen-37994b37b/"><img src="https://skillicons.dev/icons?i=linkedin" height="52" alt="LinkedIn" /></a>
&nbsp;&nbsp;&nbsp;
<a href="mailto:berattaic@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="52" alt="Email" /></a>

<sub>Feel free to reach out on LinkedIn or by email.</sub>

</div>
