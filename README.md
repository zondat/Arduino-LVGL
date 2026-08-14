<img width="2128" height="977" alt="1786724061237_194587777588188069_121543298629946553_3feac1d803ee4488e49f397aab7ba223" src="https://github.com/user-attachments/assets/d8143785-53ce-4e19-b0f0-be28b755d502" />
I create a demo that bridges LVGL with Arduino that eases completely HMI process, forever.
LVGL (https://lvgl.io/) is new technology to create embeded UI. It provides really beatiful widgets that runs on embedded devices. As I know, at the moment, there are no complete guide that bridges LVGL and Arduino but It is really simple and I want to create one.

The steps to follow:
(1) Download SquareLine Studio, it is a free software for PERSONAL USE.
(2) Design your UI in SquareLine Studio, simply drag and drop.
<img width="1919" height="1039" alt="image" src="https://github.com/user-attachments/assets/4f9f1169-7fc7-4fe9-acf3-8ac6238fcdf1" />
(3) Export your UI
- Config your project including: File->Project Settings
<img width="881" height="233" alt="image" src="https://github.com/user-attachments/assets/6e61b58f-9fda-41e8-850b-f2ce5b710e23" />
- Export->Export UI Files
<img width="571" height="257" alt="Capture" src="https://github.com/user-attachments/assets/53614c63-059b-4a94-8f1c-aedb3df8042d" />
(4) Create new project Arduino and copy-paste all ui-generated files into this folder
(5) Finally, reference the UI in the code by:  #include "ui.h" and initiates by: ui_init()

The result:
<img width="2128" height="977" alt="1786724061237_194587777588188069_121543298629946553_3feac1d803ee4488e49f397aab7ba223" src="https://github.com/user-attachments/assets/a2378c45-7ffb-42b1-8ce2-37dd7c4808fb" />


