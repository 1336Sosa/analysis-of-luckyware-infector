# analysis-of-luckyware-infector
the analysis of the luckyware imgui infector


So recently i was infected by luckyware and i reinstalled windows VIA usb, now the issue i ran into was all my srcs codes not js vcxproj was now infected by malware. The first step i did was to search for links in my src which obv i had no luck in doing so. I then went to the luckyware source code and looked at the infector code and found that it infects "imgui_impl_win32.cpp". It will place hashed code and a system command to run it as seen in the screenshots below. To remove this simply remove the hashed code and the System command it calls.<img width="1534" height="552" alt="image" src="https://github.com/user-attachments/assets/8e6dac76-5335-4f53-8df3-60a7b0848c31" />
<img width="1534" height="591" alt="image" src="https://github.com/user-attachments/assets/f9b19d89-6cfe-4281-99c1-4f8af125f1ca" />
