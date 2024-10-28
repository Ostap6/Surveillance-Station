## [Surveillance Station 9.1.1-10728](https://archive.synology.com/download/Package/SurveillanceStation)
---
### Планировщик задач

- Панель управления -> Планировщик задач. 
- Создать -> Запланированное задание -> Пользовательский сценарий. 
- Общие: Пользователь = root, снимите флажок Включить. 
- Настройки задачи: Пользовательский сценарий = ... 
- ОК - ОК 
- Нажмите и запустите задачу. 
- Удалите эту задачу, когда увидите, что имеется 58 лицензий.
---
### A. x86_64 (9.1.1-10728)
- Link download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.1.1-10728/SurveillanceStation-x86_64-9.1.1-10728.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/Kaitiz/Surveillance-Station/main/lib/SurveillanceStation-x86_64/install_license)
```

### B. x86_64_openvino (9.1.1-10728)
- Link download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.1.1-10728/SurveillanceStation-x86_64-9.1.1-10728_openvino.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/Kaitiz/Surveillance-Station/main/lib/SurveillanceStation-x86_64_openvino/install_license)
```

### C. armada38x (9.0.2-10061)
- Link download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.0.2-10061/SurveillanceStation-armada38x-9.0.2-10061.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/Kaitiz/Surveillance-Station/main/lib/SurveillanceStation-armada38x/install_license)
```

---
### Remove license
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/Kaitiz/Surveillance-Station/main/lib/license/remove_license)
```
