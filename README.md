# instagram-dm
 Selenium based library that automates direct messaging to instagram accounts

## How to use

```py
from dm import initialize_driver, login, send_msg

driver = initialize_driver()
login(driver, username, password)

send_msg(driver,to_username,msg)
```
