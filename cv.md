# Yaroslav Demyanchuk

# About me:
Electronics Engineer. I have many skills that arose in the process of work and my hobbies:
+ Electronics
   + Repair (ups, power supply and other devices, including machine controllers/various specialized controllers)
   + 3D printers (their assembly and setup)
+ electrician, design and assembly of electrical panels, connection
+ AV engineers (participate in project launches)
+ Network Engineer (copper and fibre optic), IP-CCTV
+ 3D modeling (SolidWorks)
+ Automation, smart home
+ Fire and security alarm system (Installation, maintenance and configuration)

# Contacts:
Discord: @atmega

My site: atmega.ru


# Skills:
Programming Languages: Python, C# (AVR microcontroller)

OS: ubuntu server, TrueNAS
 

# Code examples:
```
    def editreg(self, reg=int, value=str):
        """
        Редактор регистров
        """
        setvalue=int(value, 16)
        self.terminalmode_prog()

        origreg = self.cmd(b"\x30", 2)
        while 1:
            if int(origreg, 16) == setvalue:
                self.terminalmode_sm()
                return True
            if int(origreg, 16) < setvalue:
                origreg = self.cmd(b'+', 2)
            if int(origreg, 16) > setvalue:
                origreg = self.cmd(b'-', 2)
```

# Education:
Kramer Control System Programmer, Designer

Kramer certificate basic level, AV Systems design. 
