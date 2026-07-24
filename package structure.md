gcode_sender/
├── CMakeLists.txt
├── package.xml
├── README.md
├── scripts/
│   └── gcode_sender_node.py          # 主节点文件（可执行）
├── src/
│   └── gcode_sender/
│       └── __init__.py
├── msg/
│   ├── PrinterStatus.msg
│   ├── PrintProgress.msg
│   └── TemperatureInfo.msg
├── srv/
│   ├── StartPrint.srv
│   ├── PausePrint.srv
│   ├── ResumePrint.srv
│   ├── StopPrint.srv
│   ├── SetSpeed.srv
│   └── GetStatus.srv
├── launch/
│   └── gcode_sender.launch
├── config/
│   └── gcode_sender_params.yaml
└── test/
    └── test_gcode_sender.py