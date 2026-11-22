# NIC Tuner - Developed by Max

A lightweight Windows desktop utility built with **C#** and **WinUI 3** featuring a Mica backdrop, custom title bar integration, streamlined navigation, and system/network optimization tools—including the **NIC Tuner**.

---

## Overview

**NIC Tuner - Developed by Max** is designed to give users a clean, distraction-free interface to manage Windows services and tune network adapter behavior for responsive system performance.

### NIC Tuner
> Optimizes your Network Interface Controller (NIC) settings to reduce network latency, minimize packet drops, and improve connection stability. It adjusts adapter parameters—like interrupt moderation, queues, offload features, and power-saving states—for more responsive traffic handling.

---

## Key Features

* **Modern WinUI 3 Interface:** Styled with a `MicaBackdrop`, custom `TitleBar` (`ExtendsContentIntoTitleBar = true`, `Tall` title bar height), and custom application icon (`Assets/AppIcon.ico`).
* **Streamlined Navigation:** Uses a `NavigationView` (`IsSettingsVisible="False"`) with `Home` and `About` pages hosted inside a `Frame` (`NavFrame`), plus back-button and pane-toggle support.
* **NIC Tuner:** Targets network adapter parameters such as interrupt moderation, queues, offload features, and power-saving states to lower latency and improve stability.
* **Extensible Page Architecture:** Pages are organized under `NIC_Tuner___Developed_by_Max.Pages` (`HomePage`, `AboutPage`, and additional feature views).

---

## Project Structure

```text
NIC_Tuner___Developed_by_Max/
├── Assets/
│   └── AppIcon.ico
├── Pages/
│   ├── AboutPage.xaml
│   ├── AboutPage.xaml.cs
│   ├── AdapterSettingsPage.xaml.
│   ├── AdapterSettingsPage.xaml.cs
│   ├── AutoDscpFsePage.xaml.
│   ├── AutoDscpFsePage.xaml.cs
│   ├── AutoMtuPage.xaml.
│   ├── AutoMtuPage.xaml.cs
│   ├── DriverFinderPage.xaml.
│   ├── DriverFinderPage.xaml.cs
│   ├── NetshPage.xaml.
│   ├── NetshPage.xaml.cs
│   ├── NetworkInfoPage.xaml.
│   ├── NetworkInfoPage.xaml.cs
│   ├── OffloadsPage.xaml
│   ├── OffloadsPage.xaml.cs
│   ├── PowerrPage.xaml
│   ├── PowerPage.xaml.cs
│   ├── ResetPage.xaml
│   ├── ResetPage.xaml.cs
│   ├── TcpIpPage.xaml
│   ├── TcpIp.xaml.cs
│   ├── HomePage.xaml
│   ├── HomePage.xaml.cs
├── MainWindow.xaml
├── MainWindow.xaml.cs
└── NIC_Tuner___Developed_by_Max.csproj
└── TweakRunner.cs
└── TweakUi.cs
