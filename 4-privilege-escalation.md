# Privilege Escalation

| **Configuration Rule**                                                        | **Value** | **+**                                                 | **-**                                                                     |
|----------------------------------------------------------------------------------|----------------|------------------------------------------------------------|--------------------------------------------------------------------------------|
| Only login as user with standard privileges                                      | -              | UAC bypasses are prevented                      | -                                                                              |
| Prevent access to registry editing tools / Disable regedit from running silently | Enabled / Yes  | UAC bypasses via registry entries are prevented | The registry cannot be edited at all                                           |
| UAC: Only elevate executables that are signed and validated           | Enabled        | Only trusted executables are elevated                      | Custom and less known executables, that require elevation, cannot run properly |
