# N0kontzzz Kernel for POCO F4 (munch)

Custom kernel for POCO F4 (munch) focused on **root hiding** and stability. Based on N0Kernel by EmanuelCN & its fork by Impqxr with various optimizations and additional features.

## 🚀 Key Features

- **Root Hiding**: Special optimizations to hide root access from banking apps and games
- **High Stability**: Based on proven stable N0Kernel
- **Optimal Performance**: Optimized for gaming and daily usage
- **Additional Features**: DC Dimming, BBRv3, and Bypass Charging
- **Multiple Variants**: 3 variants available to suit your needs
- **Wide ROM Compatibility**: Works on AOSP, MIUI/HyperOS, and AOSP with IR from LOS
- **Smart Installation**: Auto-detects ROM type or allows manual selection

## 📱 Supported Device

This kernel is specifically designed for:

| Codename | Device Name |
|----------|-------------|
| munch | POCO F4 / Redmi K40S |

## 🔧 Available Variants

### 1. **Standard Variant**
- Standard kernel without root solution
- Perfect for users who don't need root access
- Focus on stability and performance

### 2. **KernelSU Next**
- Equipped with KernelSU Next
- Modern root solution with advanced features
- Better module management support

### 3. **KernelSU Next + SUSFS**
- KernelSU Next with SUSFS (Super User File System)
- Most advanced root hiding capabilities
- Perfect for bypassing banking apps and anti-cheat games

## 🛠️ Installation

### Requirements
- Unlocked bootloader
- Custom recovery (TWRP/OrangeFox) or fastboot
- Compatible ROM: **AOSP, MIUI/HyperOS, or AOSP with IR from LineageOS**
- Stock kernel backup (highly recommended)

### Installation Methods

#### Method 1: Auto-Detection via File Name
The kernel will automatically detect your ROM type based on the filename:

1. **For MIUI/HyperOS**: Rename the zip file to include `-miui` (e.g., `N0Kontzzz-v1.0-miui.zip`)
2. **For AOSP with IR from LOS**: Rename the zip file to include `-ir` (e.g., `N0Kontzzz-v1.0-ir.zip`)
3. **For Standard AOSP**: Use the original filename
4. Flash via custom recovery as normal

#### Method 2: Manual Selection (ADB Sideload or Unnamed Files)
If using ADB sideload or the filename doesn't contain ROM identifiers:

1. Boot to custom recovery
2. Flash the kernel zip file
3. **Use volume buttons to select your ROM type:**
   - **Vol Down**: Navigate through options (miui → ir → default)
   - **Vol Up**: Select current option
4. The installer will show: `> Option selected: [ROM_TYPE] (Vol–=Next Vol+=Select)`

## ⚠️ Disclaimer

**I AM NOT RESPONSIBLE IF YOUR DEVICE GETS BRICKED!**

You flash this kernel at your own risk. Make sure to create a stock kernel backup before installation.

## 🤝 Credits

- **@EmanuelCN**: N0Kernel development
- **@rifsxd**: KernelSU-Next
- **@simonpunk & @sidex15**: SUSFS
- **@Impqxr**: N0Kernel fork & help
- **@osm0sis**: AnyKernel3 framework
- **Kernel developers**: Cherry-picked commits
- **Google**: Clang compiler
- **All testers and contributors**: For their valuable feedback and support

## 📞 Support & Feedback

- **Telegram Group**: [https://t.me/PocoF4Indonesia]
- **GitHub Issues**: Use GitHub Issues to report bugs

## 📄 License

This project uses GPL v2 license in accordance with the Linux kernel.

---

**If this kernel is useful for you, don't forget to give a ⭐ star to this repository!**
