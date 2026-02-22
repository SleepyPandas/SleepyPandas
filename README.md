<div align="center">

  <h1>Its me, Anthony Hua!</h1>
  <img src="https://i.pinimg.com/originals/a9/84/cc/a984cc337b3bbfdbeb8040acb2017b46.gif" width="150" />
  <img src="https://i.pinimg.com/originals/a9/84/cc/a984cc337b3bbfdbeb8040acb2017b46.gif" width="150" />
  <img src="https://i.pinimg.com/originals/a9/84/cc/a984cc337b3bbfdbeb8040acb2017b46.gif" width="150" />
  <br>

  <a href="https://www.linkedin.com/in/anthony-hua-5638382ba/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:tommyrobotics1@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<br>

## About Me
### Embedded & Firmware | C, Python | Bare-Metal
I’m a student at the University of Toronto studying Computational Cognitive Science
and Mathematics, with a strong interest in embedded systems and firmware development.

I’m currently building projects in **bare-metal C and Python** to better understand
microcontrollers, hardware interfaces, and low-level system behavior. My focus is on writing drivers from scratch, working with SPI/I²C/UART/Timers + more, and building
tooling to debug and visualize hardware data.

<div align="center">
  <img src="https://img.shields.io/badge/Powered%20by-Matcha-00C942?style=for-the-badge&logo=coffee&logoColor=white" />
  <img src="https://img.shields.io/badge/Works%20on%20my%20machine-approved-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Has%205%20Toes-Yes-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Sushi%20Chef-True-red?style=for-the-badge" />
</div>

<br>



<br>

## Things I've worked with 

<div align="center">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/latex-008080?style=for-the-badge&logo=latex&logoColor=white" />
  <img src="https://img.shields.io/badge/jupyter%20notebook-%23FA0F00.svg?style=for-the-badge&logo=Jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=rstudio&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=2f9fe3" />
</div>

<br>

## Featured Projects

### [🐻 MPU6500 Bare Metal Driver](https://github.com/SleepyPandas/MPU6500-Bare-Metal-Driver)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-de0434?style=flat&logo=cmake&logoColor=white)
> A **platform-agnostic, register-level driver** for the MPU6500 IMU on **STM32H5 (Cortex-M33)**. 
> Features a **non-blocking DMA state machine** to free up CPU cycles, function-pointer HAL abstraction for portability, and automated gyroscope calibration. Includes a real-time Python dashboard that visualizes live sensor data via UART.

<details>
  <summary><b> Watch Demo: Live Dashboard & Hardware</b></summary>
  <br>
  <video src="https://github.com/user-attachments/assets/083083cf-58ff-4d32-9ef0-c8d85db2905d" controls width="100%"></video>
</details>

### [🤖 Discord LaTeX Bot](https://github.com/SleepyPandas/Discord-LaTeX-Bot)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![AsyncIO](https://img.shields.io/badge/AsyncIO-EF3340?style=flat&logo=files&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale-000000?style=flat&logo=tailscale&logoColor=white)


> A discord bot that renders LaTeX/TikZ diagrams into images in real-time.
> Built with **asyncio** and **ThreadPoolExecutor** to offload CPU-intensive compilation tasks, ensuring the main event loop remains non-blocking.
>
> Features **Dockerized deployment** and integrates **Google's Gemma API** for natural language Q&A.
> Created an analytics dashboard to monitor LaTeX compile performance (requests/success/error rate), visualize trends, and inspect recent compile events for debugging. With OPS networking via Tailscale.

<details>
  <summary><b> See Dashboard with sample data below!</b></summary>
  <br>
   <img width="1000" height="1269" alt="Discord Bot Dashboard" src="https://github.com/user-attachments/assets/ae52a177-85d4-440f-95be-efec103b2bf9" />
</details>

### [📄 Seamless PDF Python Package](https://github.com/SleepyPandas/Document-to-ContinuousPDF)
[![PyPi](https://img.shields.io/pypi/v/seamless-pdf?label=PyPi%20Release&color=7700b8&style=flat)](https://pypi.org/project/seamless-pdf/) [![Downloads](https://static.pepy.tech/badge/seamless-pdf)](https://pepy.tech/project/seamless-pdf) ![Python Versions](https://img.shields.io/badge/python-3.10%20%7C%203.11%20%7C%203.12%20%7C%203.13-007ec6?style=flat) [![CI](https://img.shields.io/github/actions/workflow/status/SleepyPandas/Document-to-ContinuousPDF/test.yml?style=flat&label=tests)](https://github.com/SleepyPandas/Document-to-ContinuousPDF/actions) [![License](https://img.shields.io/github/license/SleepyPandas/Document-to-ContinuousPDF?style=flat)](https://github.com/SleepyPandas/Document-to-ContinuousPDF/blob/main/LICENSE)

> A Python utility and CLI for converting HTML/Markdown/Docx into continuous, scrollable PDFs without page breaks while maintaing Table of Contents and CSS Styling for github MD includes margin / width adjustments.
> 
> Uses **Chromium instance via Playwright** to render DOM elements extracting dimensions. 

&#x25B6;&#xFE0E; [Pypi Package Website](https://pypi.org/project/seamless-pdf/)

### [🤖 DHT11 Bit-Banging Driver](https://github.com/SleepyPandas/DHT11-Bit_Banging-Driver)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white) ![Bare Metal](https://img.shields.io/badge/Bare%20Metal-555555?style=flat&logo=chip&logoColor=white)

> A **bare-metal C driver** implementing the custom DHT11 single-wire protocol from scratch on **STM32H5**.
> Manually controls GPIO timing with **microsecond precision** (using hardware TIM1) to handle the sensor's strict handshaking and data transmission states. Includes native **checksum verification** to reject corrupted data frames.

### [♿ Moral Machine Dataset Analysis](https://github.com/SleepyPandas/COG260-Project-Moral-Machine-Analysis)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)

> A reproducible data pipeline analyzing **millions of Moral Machine rows** to link cultural metrics (Rule of Law, Individualism) with ethical choices. 
> Implements **memory-efficient CSV streaming**, **OLS regression**, and **Pearson/Spearman correlation** 

### [🎨 Figma Discord Rich Presence](https://github.com/SleepyPandas/Figma-Discord-Rich-Presence)
![GitHub Tag](https://img.shields.io/github/v/tag/SleepyPandas/Figma-Discord-Rich-Presence?style=flat&logo=github&label=Release&color=7700b8) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![Inno Setup](https://img.shields.io/badge/Inno%20Setup-264653?style=flat&logo=windows&logoColor=white) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat&logo=apple&logoColor=white)


> A **cross‑platform Go utility** that syncs active Figma Desktop file/project context to Discord Rich Presence
> with **smart window detection**, **auto‑reconnect**, and a **privacy/config UI** (v2).
> Packaged for **Windows (.exe) and macOS (.pkg)** with minimal setup.

&#x25B6;&#xFE0E; [Website + Download Here!](https://sleepypandas.github.io/Figma-Discord-Rich-Presence/)

<br>

## GitHub Stats
<table align="center">
  <tr>
    <td align="center" width="50%">
        <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=u559ks56bbgkxkgpkxmttmt9g&cover_image=true&theme=default&show_offline=false&background_color=0e1117&interchange=false&profanity=false&bar_color=00fbff&bar_color_cover=false" alt="Spotify Status" />
      </a>
    </td>
    <td align="center" width="50%">
        <img src="https://github-stats-private-2.vercel.app/api/top-langs/?username=SleepyPandas&layout=compact&theme=tokyonight&langs_count=8&hide=TeX,BibTeX%20Style,HTML,CSS&exclude_repo=Finance-Project,Cog260-Labs,Newsletters-HTML&"v=1" alt="Top Langs" />
      </a>
      <br><br>
      <img width="300" alt="Discord bot contribution" src="https://github.com/user-attachments/assets/7ac96b67-8eb7-409b-b17b-d7c3a5c9a9b5" />
    </td>
  </tr>
</table>



