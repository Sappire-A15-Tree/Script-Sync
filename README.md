## Clone Device Trees

```bash
# Clone Device Trees for Sapphire
echo "Cloning Device Trees for Sapphire..."

rm -rf device/xiaomi/sapphire-kernel
git clone --depth 1 -b lineage-22.2 https://github.com/Sappire-A15-Tree/device_xiaomi_sapphire-kernel device/xiaomi/sapphire-kernel

rm -rf device/xiaomi/sepolicy
git clone --depth 1 -b 15 https://github.com/Sappire-A15-Tree/device_xiaomi_sepolicy device/xiaomi/sepolicy

rm -rf device/xiaomi/sapphire
git clone --depth 1 -b lineage-22.2 https://github.com/Sappire-A15-Tree/device_xiaomi_sapphire device/xiaomi/sapphire

rm -rf vendor/xiaomi/sapphire
git clone --depth 1 -b lineage-22.2 https://github.com/Sappire-A15-Tree/vendor_xiaomi_sapphire vendor/xiaomi/sapphire

rm -rf hardware/xiaomi
git clone --depth 1 -b lineage-22.2 https://github.com/Sappire-A15-Tree/android_hardware_xiaomi hardware/xiaomi

echo "============================"
echo "Device Trees cloned successfully"
echo "============================"
```
