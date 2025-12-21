# 📚 unbound
Modified unbound configuration for speed (caching), security (hardened), privacy and IPv6 enabled

* Place this custom config in your .../unbound.conf.d - folder
* You can rename it to your preffered .conf-filename
* **INFORMATION**:
  * Since unbound is usually used with other DNS services (e.g., Pi-Hole, Adguard Home)
    which already listen on DNS port 53, the port was changed to **5335**.
  * You can change it everytime in the configuration file to your needs

