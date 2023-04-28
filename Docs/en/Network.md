![Network](https://user-images.githubusercontent.com/36089626/235139504-e50451c5-2733-4568-b86f-20367b3215a6.png)

1. The name of the UPS that appears in the title of the page.
2. Local WiFi network name
3. Password to the local WiFi network
4. Hide/unhide module access point visibility
5. Password to the access point of the module (default "12345678")
6. Using a static or dynamic IP address of the module
7. Static IP address of the module
8. Network port of the module in the local network (may be needed when reassigning and forwarding the port for access from outside the local network)
9. Gateway IP address
10. Netmask
11. DNS server IP address
12. Activation of the MQTT protocol
13. MQTT broker IP address
14. MQTT port
15. MQTT username
16. MQTT user password
17. Read / publish MQTT topic (topic is a unique ID of the module. This ID will also be used in the DNS address of the module)
   - to manage UPS, the following messages should be sent to the topic:
     | Topic | Message | Result |
     |-------|-----------|-----------|
     |ups_id/set|reboot| Reboot |
     |ups_id/set/ups_turn_off| - | Switch output OFF|
     |ups_id/set/ups_turn_on| - | Switch output ON|
     |ups_id/set/ups_go_test| - | Launch Self-Test|
     |ups_id/set/ups_get_error| - | Request statuses / errors|
     |ups_id/set/ups_run_time| - | Battery calibration|
     |ups_id/set/ups_go_upd| - | Update module|
18. Enable Module Discovery in Home Assistant (HASS MQTT Discovery)
19. Enable sending a command via SSH to a remote computer when the battery discharge threshold is passed. For example, send the command "sudo shutdown now" to gracefully shutdown if the UPS may shut down due to low batteries
20. Address of a computer managed via SSH in the local network
21. Computer port
22. SSH username
23. SSH password
24. SSH command line
25. Battery level in %% at which a command will be sent via SSH
26. Button for testing communication and sending a test command via SSH
27. Activate SMTP mail client
28. DNS name of the SMTP server
29. PORT SMTP server
30. Sender's address
31. Sender password
32. Recipient's name
33. Recipient's address
34. Event list for sending messages
