![image](https://github.com/acam4890/RSLogix-Simulation-Projects/assets/130267975/8025d704-9908-49e2-9f23-a496eeb22edd)

This is another pump control program but this time it implements an alarm system and Hand, Off, Auto mode controls. In "off" mode, the program does what you'd expect... nothing. In "hand" mode, the program allows the operator to manually power the pump for as long as they hold down the "hand mode" button. In "auto" mode, the program powers the pump for 30 seconds and keeps it powered down for 10 seconds repeatedly. If the pressure sensor reads a pressure value over 30 PSI while the pump is on for 5 seconds, an alarm is raised. If the flow switch does not detect anything flowing while the pump is on for 5 seconds, an alarm is raised. In both cases, an alarm being raised also lights up the respective alarm indicator and moves the program into "off" mode. The alarm reset button can be pressed if the operator believes the issue is fixed so they can resume operating the pump system. However, if the condition that set off the alarm is still present, the alarm will be set off again after 5 seconds of the pump being on. The alarm silence button can be pressed by the operator if they wish to fix the issue without the alarm indicator bothering them. The alarm silence does not disable the alarm so the alarm indicator will stay of unless the alarm reset is pressed and the alarm is set off again.
