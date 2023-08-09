# history_usb_payload

### 🛠️ How it works

 -- > This payload is designed to exfiltrate the public IP address and bash history to a Discord Webhook Server. You will need a rubber-ducky or Raspberry Pi Pico to test the script.

It starts by opening a shell, sending the target machine's public IP address to a Discord WebHook. Then, it creates a bash script, which is executed in the background mode using the ```&``` symbol. The script continuously sends history commands to the same Discord webhook, one line at a time, indefinitely (or until detected). This is a straightforward project aimed at enhancing a little bit my understanding of payloads and cybersecurity in general. Currently, it is compatible only with Linux devices using US or UK keyboard layouts.


#### Italian keyboard layout is coming soon..

