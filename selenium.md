# Selenium notes
## Errors
* Not calling `driver.quit()` will result in the browser not closing.
* Calling `driver.quit()` before you are done can result in a `SessionNotFound` error.