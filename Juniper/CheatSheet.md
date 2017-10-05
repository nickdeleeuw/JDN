# Juniper

## Basics
| Task                      | Command                                |
| :---                      | :---                                   |
| Reboot the system         | `request system reboot` |
| Shutdown the system         | `request system power-off` |
| Enter operational mode    | `cli`       |
| Enter configuration mode    | `edit`       |
| Commit the changes made on the system(s).     | `commit (synchronize)`       |

## Devices
| Task                      | Command                                |
| :---                      | :---                                   |
| Mount usb device        | `mount –t msdos /dev/da1s1 /mnt` |
| Unmount usb device   | `umount /mnt`       |

## Firmware
| Task                      | Command                                |
| :---                      | :---                                   |
| Upgrade to certain software package.         | `request system software add /<location>/<name of junos package> reboot` |

## User
| Task                      | Command                                |
| :---                      | :---                                   |
| Change user password       | `edit system login user "username"` |
|       | `set authentication plain-text-password ` |

## Case Small Setup
| Task                      | Command                                |
| :---                      | :---                                   |
| Set RSTP mode PTP on WAN port       | `set protocols interface ge0/0/8 mode point-to-point` |

