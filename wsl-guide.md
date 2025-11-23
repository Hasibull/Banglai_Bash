💻 **WSL (Windows Sub-system for Linux)** হলো Windows 10/11 এর ভিতরে Linux চালানোর একটি Light-weight, দ্রুত এবং নেটিভ উপায়। এর জন্য আলাদা Virtual Machine বা Dual Boot দরকার হয় না!

#### 🔧 Install করার প্রসেস:
Powershell (administrator mode এ) চালু করে নিচের command টি run করলে, এটি WSL ও Ubuntu এর 22.04 (বা অন্য version) Dwonload ও Install করবে!
```powershell
wsl --install
```

Linux এর কি কি Distro বর্তমানে available আছে তা দেখার জন্য -
```powershell
wsl --list --online
```
আমার PC/Laptop এ Linux এর কি কি Distro বর্তমানে install করা আছে তা দেখার জন্য -
```powershell
wsl --list
```
কোন নির্দিষ্ট Distro Install করার জন্য -
```powershell
wsl --install -d Distro_name
i.e. wsl --install -d Ubuntu
```
Install থাকা কোন Distro কে Uninstall করতে হলে -
```powershell
wsl --unregister Distro_name
i.e. wsl --unregister Ubuntu
```
#### 📝 WSL এর প্রয়োজনীয় কিছু command:
কোন নির্দিষ্ট Distro run করার জন্য -
```powershell
wsl -d Distro_name
i.e. wsl -d Ubuntu
```
