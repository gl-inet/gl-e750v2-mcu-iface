1.Use scp to upload oled_contorl to /usr/bin/ directory,Execute 'chmod 775/usr/bin/oled_contorl' to add permissions
2.For detailed usage, please execute 'oled_contorl help'

3.Example---1
    Display 5gwifi page：Execute 'oled_contorl wifi_5g off'
    Enable 5gwifi page：Execute 'oled_contorl wifi_5g on'

4.Example---2
    Read battery information and temperature: Execute 'oled_contorl mcu-status read'
    return value: "Battery_capacity= 100,temperature= 34.5,Charging_state= 10,Charging cycle= 10"

5.Example---3
    Display custom information page：'oled_contorl custom on <custom_info>'