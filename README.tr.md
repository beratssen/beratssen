<div align="center">

[English](README.md) · **Türkçe**

<img src="assets/neofetch.svg" width="100%" alt="neofetch: berat@github" />

</div>

<br>

## Hakkımda

- 🧊 Fotoğraflardan **3D model** üretiyorum (fotogrametri) ve **Blender**'da temizliyorum: mesh düzenleme, UV mapping, optimizasyon
- 📱 Unity ile **artırılmış gerçeklik restoran menüsü** geliştirdim: telefonu menüye tut, yemek 3D olarak karşında belirsin
- 🛡️ TryHackMe üzerinden uygulamalı **siber güvenlik** çalışıyorum: ağ temelleri, Linux/Windows terminali, Nmap, Wireshark, Metasploit
- 🧭 **İnsan-bilgisayar etkileşimi** üzerine ders aldım: UI/UX'i standartlara göre tasarlama, **Figma** ile prototipleme
- 🧑‍💻 **C, C++ ve C#** yazıyorum, **SQL** biliyorum; web tarafında React, HTML, CSS ve JavaScript kullanıyorum

<br>

## Teknolojiler

**3D ve AR**<br>
<img src="https://skillicons.dev/icons?i=blender,unity&perline=8" alt="3D ve AR" />
&nbsp;![Vuforia](https://img.shields.io/badge/Vuforia-AR-0F9D58?style=for-the-badge)
![RealityScan](https://img.shields.io/badge/RealityScan-Fotogrametri-black?style=for-the-badge)

**Güvenlik ve sistemler**<br>
<img src="https://skillicons.dev/icons?i=linux,powershell,git&perline=8" alt="Sistemler" />
&nbsp;![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596D1?style=for-the-badge&logo=metasploit&logoColor=white)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)

**Diller**<br>
<img src="https://skillicons.dev/icons?i=c,cpp,cs,mysql&perline=8" alt="Diller" />

**Web**<br>
<img src="https://skillicons.dev/icons?i=react,html,css,js,figma&perline=8" alt="Web" />

<br>

## Öne çıkan: AR Restoran Menüsü

Menüdeki QR kodu telefonla okut, yemek masanın üzerinde 3D olarak belirsin. Sipariş vermeden önce porsiyonu ve sunumu görürsün. Her yemek gerçek bir tabaktan fotoğraflanıp fotogrametri ile yeniden oluşturuldu, Blender'da temizlendi ve mobil için optimize edildi.

<table align="center">
  <tr>
    <td align="center"><img src="assets/turntable-pirzola.gif" width="220" alt="Pirzola 3D model" /><br><sub>Pirzola &amp; patates</sub></td>
    <td align="center"><img src="assets/turntable-makarna.gif" width="220" alt="Makarna 3D model" /><br><sub>Makarna</sub></td>
    <td align="center"><img src="assets/turntable-tost.gif" width="220" alt="Tost 3D model" /><br><sub>Tost</sub></td>
  </tr>
</table>

**Unity · Vuforia · C# · Blender · RealityScan · Figma**

<details>
<summary><b>Nasıl yaptım</b></summary>
<br>

1. **Çekim:** her yemek için tabağın etrafında, farklı yüksekliklerden yaklaşık 100 fotoğraf.
2. **Yeniden oluşturma:** aynı yemeği Kiri Engine ve RealityScan ile karşılaştırdım. RealityScan daha detaylı çıktı, tüm nihai modeller onunla üretildi.
3. **Blender'da temizlik:** masayı ve fazlalık geometriyi sildim, bozuk mesh bölgelerini onardım, UV sorunlarını düzelttim.
4. **Mobil optimizasyon:** Decimate ile modelleri ~3 milyondan ~50 bin poligona, dokuları 4K'dan 2K'ya indirdim. Android'deki takılma bitti.
5. **İşaretleyici takibi:** Python ile üretilmiş QR kod, Vuforia image target olarak 5/5 algılanabilirlik puanı aldı.
6. **Arayüz tasarımı:** Figma'da tasarlayıp Unity'de kategori sekmeleri ve ileri/geri gezinmeyle kurdum.

</details>

<br>

## 3D çalışmalarım: fotoğraftan sırt çantaları

Gerçek sırt çantalarını hafif 3D modellere dönüştürdüm (şu ana kadar 13 tasarım). Fotogrametri nadiren tertemiz çıkar. Bu yüzden işin büyük kısmı Blender'da bozuk bölgeleri düzeltmekti: elle **mesh düzenleme**, düzgün alanların **UV haritasını** bozuk alanlara uygulama ve modeli hafif kalması için sadeleştirme.

<table align="center">
  <tr>
    <td align="center"><img src="assets/turntable-red.gif" width="220" alt="Kırmızı sırt çantası 3D model" /></td>
    <td align="center"><img src="assets/turntable-heart.gif" width="220" alt="Kalp desenli sırt çantası 3D model" /></td>
    <td align="center"><img src="assets/turntable-teal.gif" width="220" alt="Turkuaz sırt çantası 3D model" /></td>
  </tr>
</table>

<br>

## Yeteneklerim

| Alan | Neler yapıyorum |
| --- | --- |
| **3D** | Fotogrametri, mesh temizleme, UV mapping, Blender'da poligon ve doku optimizasyonu |
| **AR** | Unity + Vuforia ile işaretleyici tabanlı AR, mobil performans iyileştirme |
| **Güvenlik** | TryHackMe odaları, ağ temelleri, Nmap, Wireshark, Metasploit, Linux ve Windows komut satırı |
| **UI / UX** | Figma'da arayüz tasarımı, kullanılabilirlik ve HCI standartları, tasarımdan koda geçiş |
| **Web** | React, HTML, CSS, JavaScript |

<br>

## İletişim

<div align="center">

<a href="https://www.linkedin.com/in/berat-%C5%9Fen-37994b37b/"><img src="https://skillicons.dev/icons?i=linkedin" height="52" alt="LinkedIn" /></a>
&nbsp;&nbsp;&nbsp;
<a href="mailto:berattaic@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="52" alt="E-posta" /></a>

<sub>LinkedIn ya da e-posta üzerinden bana ulaşabilirsin.</sub>

</div>
