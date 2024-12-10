## Network Connections Viewing Commands

The following commands can help you view active network connections and identify which processes are using them.

- **To list all open files and network connections:**
  
  ```bash
  sudo lsof -i -P -n
  ```

- **To filter the list for Apache-related connections:**
  ```bash
  sudo lsof -i -P -n | grep apache
  ```
