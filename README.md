# 📶 Wi-Fi Deauthentication

Wi-Fi Deauthentication is a simple educational project that demonstrates how deauthentication attacks work on wireless networks. The project sends deauth packets to disconnect devices from a target Wi-Fi network in a controlled environment, helping understand wireless communication behavior and network disruption.

---

## 🚀 Features

- Demonstrates Wi-Fi deauthentication attacks  
- Disconnects clients from a selected wireless network  
- Works on Linux systems with compatible wireless adapters  
- Easy to understand and run for learning purposes  

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Tools Used:** aircrack-ng (aireplay-ng, airodump-ng)  
- **Operating System:** Linux  

---

## 📂 Project Structure

```text
Wifi-Deauthentication/
├── deauth.py        # Main Python script
├── README.md        # Project documentation
└── LICENSE          # License file
```

---

## ⚙️ Requirements

Before running this project, ensure you have:

- A Linux-based system (Kali Linux, Ubuntu, Parrot OS, etc.)
- A wireless adapter that supports monitor mode
- aircrack-ng suite installed

Install aircrack-ng using:

```bash
sudo apt update
sudo apt install aircrack-ng
```

---

## ▶️ Usage

1. Enable monitor mode on your wireless interface:

```bash
sudo airmon-ng start wlan0
```

2. Run the deauthentication script:

```bash
sudo python3 deauth.py
```

3. Follow the on-screen instructions to select the target network.

---

## ⚠️ Disclaimer

This project is intended **strictly for educational and research purposes**.  
Only test on networks you own or have explicit permission to use.  
Unauthorized use of deauthentication attacks may be illegal.

---

## 🤝 Contributing

Contributions are welcome.  
Feel free to fork this repository and submit pull requests or suggestions.

---

## 📜 License

This project currently does not use any license. Feel free to modify for personal or educational use. For commercial/redistribution, please seek consent.

---

## 👤 Author

**[Priyanshu Khambalkar](https://github.com/18PriyanshuK)**  

