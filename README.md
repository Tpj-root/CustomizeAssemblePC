# CustomizeAssemblePC
A customizable PC price list and build reference. Easily compare components, track prices, and assemble your own PC configurations.



Got it 👍 You want to build a **structured master list** for your price tracker CSV.
Here’s a detailed breakdown for **PC parts inventory**:

---

## ✅ CSV Columns

```
Date,Shop_name,Category,Component,Brand,Model,Price(₹)
```

---

## 🖥️ Category → Component → Brand → Model Examples

### 1. **CPU (Processor)**

* **Component**: Processor
* **Brands**: Intel, AMD
* **Models**:

  * Intel: i3, i5, i7, i9 (10th → 14th gen)
  * AMD: Ryzen 3, 5, 7, 9, Threadripper

---

### 2. **GPU (Graphics Card)**

* **Component**: Graphics Card
* **Brands**: NVIDIA, AMD
* **Models**:

  * NVIDIA: GTX 1660, RTX 2060, RTX 3060, RTX 4060, RTX 4090
  * AMD: RX 5500, RX 6600, RX 6700 XT, RX 7900 XTX

---

### 3. **Motherboard**

* **Component**: Motherboard
* **Brands**: ASUS, MSI, Gigabyte, ASRock
* **Models**:

  * Intel Socket: H610, B660, Z690, Z790
  * AMD Socket: A520, B550, X570, X670

---

### 4. **RAM (Memory)**

* **Component**: Memory
* **Brands**: Corsair, G.Skill, Kingston, Crucial, TeamGroup
* **Models**:

  * DDR2 (rare), DDR3, DDR4, DDR5
  * Sizes: 4GB, 8GB, 16GB, 32GB sticks
  * Speeds: 2400MHz, 3200MHz, 3600MHz, 5200MHz

---

### 5. **Storage**

* **Component**: SSD / HDD
* **Brands**: WD, Seagate, Samsung, Crucial, Kingston
* **Models**:

  * SSD SATA: 240GB, 500GB, 1TB
  * NVMe: WD SN570, Samsung 970 Evo, Crucial P3
  * HDD: 1TB, 2TB, 4TB

---

### 6. **PSU (Power Supply)**

* **Component**: Power Supply
* **Brands**: Corsair, Cooler Master, Seasonic, Antec
* **Models**: 450W, 550W, 650W, 750W, 1000W (Bronze, Gold, Platinum)

---

### 7. **Cabinet (Case)**

* **Component**: PC Case
* **Brands**: NZXT, Cooler Master, Corsair, Lian Li, Antec
* **Models**: Mid Tower, Full Tower, Mini ITX cases

---

### 8. **Cooling**

* **Component**: CPU Cooler / Liquid Cooler
* **Brands**: Cooler Master, DeepCool, Noctua, NZXT
* **Models**:

  * Air: Hyper 212, Noctua NH-D15
  * Liquid: NZXT Kraken, Corsair H100i

---

### 9. **Monitor**

* **Component**: Display
* **Brands**: Dell, LG, Samsung, Acer, ASUS
* **Models**: 1080p 60Hz, 144Hz Gaming, 4K UHD

---

### 10. **Keyboard**

* **Component**: Keyboard
* **Brands**: Logitech, Razer, Corsair, Redragon, HyperX
* **Models**: Mechanical (Red, Blue, Brown Switch), Membrane

---

### 11. **Mouse**

* **Component**: Mouse
* **Brands**: Logitech, Razer, SteelSeries, Corsair
* **Models**: Gaming Wired/Wireless (G102, G502, DeathAdder, etc.)

---

### 12. **Laptop**

* **Component**: Laptop
* **Brands**: Dell, HP, ASUS, Lenovo, Acer, Apple
* **Models**: Gaming Laptop (ROG, Predator, Legion), Business Laptop (ThinkPad, EliteBook), MacBook Air/Pro

---

### 13. **Networking**

* **Component**: Router / LAN Card
* **Brands**: TP-Link, Netgear, ASUS, D-Link
* **Models**: WiFi 5, WiFi 6 routers, PCIe LAN cards

---

### 14. **Accessories**

* **Component**: Headset, Webcam, Speakers, UPS
* **Brands**: Logitech, Corsair, JBL, APC
* **Models**: Varies by product

---

## 📅 Example Full CSV Lines

```csv
Date,Shop_name,Category,Component,Brand,Model,Price (₹)
2025-08-19,ShopA,CPU,Processor,Intel,i5-12400F,15000
2025-08-19,ShopB,GPU,Graphics Card,NVIDIA,RTX 3060,28000
2025-08-19,ShopA,RAM,Memory,Corsair,Vengeance DDR4 16GB 3200MHz,4500
2025-08-19,ShopC,Storage,SSD,Samsung,970 EVO Plus 1TB,5200
2025-08-19,ShopB,PSU,Power Supply,Corsair,CX550 550W Bronze,4200
2025-08-19,ShopA,Case,PC Case,NZXT,H510 Mid Tower,5200
2025-08-19,ShopC,Monitor,Display,Dell,24\" 1080p 144Hz,12000
2025-08-19,ShopB,Cooling,CPU Cooler,Cooler Master,Hyper 212,2500
```

---

👉 This gives you a **clear hierarchy**:

* **Category** = Broad group (CPU, GPU, RAM, Storage…)
* **Component** = Specific type inside that category
* **Brand** = Manufacturer
* **Model** = Exact product

---



