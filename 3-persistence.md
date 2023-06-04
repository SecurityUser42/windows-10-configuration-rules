# Persistence

| **Configuration Rule**                                                                      | **Value** | **+**                                                                 | **-**                                               |
|--------------------------------------------------------------------------------------------------|----------------|----------------------------------------------------------------------------|----------------------------------------------------------|
| ASR Rule: Block process creations originating from PSExec and WMI commands | 1              | WMI cannot be abused to execute malicious commands periodically | WMI cannot be used to schedule tasks at all   |
| Remove (RX) permissions for schtasks.exe from standard users                                     | -              | Attackers cannot schedule tasks without administrative privileges          | Standard users cannot use schtasks.exe to schedule tasks |
