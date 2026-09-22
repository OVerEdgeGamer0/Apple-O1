# **Apple O1 — Full Specification Sheet**

## **Overview**
The **Apple O1** is the first chip in the O‑series, created by fusing **two A15 Bionic systems** into a single unified hybrid processor.  
It targets balanced performance for exporting, editing, AI tasks, and everyday macOS usage.

---

## **CPU Architecture**
### **Main CPU: Dual A15 Bionic**
- **Total A15 cores:** 12  
  - **4× Avalanche (Performance)**  
    - Clock: **6.46 GHz**  
  - **8× Blizzard (Efficiency)**  
    - Clock: **3.64 GHz**  
- **Caches:**  
  - **L1:** 128 KB per core  
  - **Unified L2:** 8 MB  
- **Interconnect:**  
  - Dual‑die fusion fabric  
  - Unified memory access  
  - Shared scheduling across both A15 dies

### **Co‑Processor:**  
None (P1 is exclusive to O1 Max)

---

## **GPU — O1 Graphics Engine**
- **Architecture:** Apple tile‑based deferred renderer  
- **Cores:** **10 GPU cores**  
- **Features:**  
  - Full Metal support  
  - Compute shaders  
  - Hardware tessellation  
  - Optimized for Golden Gate Render Engine  
- **Performance target:**  
  - 1080p gaming  
  - Smooth UI  
  - Real‑time effects

---

## **Neural Engine**
- **Cores:** **32‑core O1 Neural Engine**  
- **Accelerated workloads:**  
  - AI denoise  
  - Super‑resolution  
  - HDR remapping  
  - Color grading  
  - Smart masking  
  - Background removal  
- **OS integration:**  
  - Tahoe: Smart Assist  
  - Golden Gate: Pro AI Pipeline (scaled‑down vs O1 Max)

---

## **Media Engine**
- **Supported codecs:**  
  - H.264  
  - H.265 (HEVC)  
  - ProRes Lite  
  - **O1 UltraCodec** (Golden Gate exclusive)  
- **Capabilities:**  
  - Real‑time 1080p export  
  - Fast 4K preview  
  - Hardware‑accelerated timeline scrubbing  
  - AI‑enhanced preview generation

---

## **Memory & Storage**
- **Unified memory:**  
  - **16 GB LPDDR5**  
- **Bandwidth management:**  
  - GPU + NE priority lanes  
  - No P1 subsystem  
- **Storage (MacBook O1 concept):**  
  - **512 GB NVMe SSD**  
  - PCIe‑based controller

---

## **I/O**
- **Ports:**  
  - 2× USB‑C / Thunderbolt  
- **Wireless:**  
  - Wi‑Fi 6E  
  - Bluetooth 5.x  
- **Other:**  
  - High‑speed NVMe  
  - Unified sensor pipeline

---

## **Operating Systems**
### **macOS Tahoe**
- Everyday mode  
- Battery‑optimized  
- Balanced A15 usage  
- No co‑processor offloading

### **macOS Golden Gate**
- Performance mode  
- Full dual‑A15 activation  
- Includes:  
  - Golden Gate Render Engine  
  - Pro Thermal Boost  
  - O1 Hybrid Scheduler

---

## **Thermals & Power**
- **Cooling:** Active single‑fan system  
- **Thermal modes:**  
  - Standard  
  - Pro Thermal Boost  
- **Power behavior:**  
  - Avalanche handles heavy load  
  - Blizzard handles background tasks  
  - No P1 subsystem to offload work

---

## **Summary**
The **Apple O1** is the baseline hybrid chip of the O‑series:  
**Dual A15 power + upgraded GPU + strong Neural Engine + Golden Gate integration.**  
It delivers balanced performance for creators and everyday users while maintaining efficiency.
