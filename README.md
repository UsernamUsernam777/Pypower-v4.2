# pypower (New Version)
Update tidy_up logic for better grid alignment
Note: this lib is updated everytime



## 🛡️ License & Legal Protection
This project is protected by the **Creative Commons BY-NC-SA 4.0** license.
- ✅ **Free** for personal and educational use.
- ❌ **Commercial use or selling this code is STRICTLY PROHIBITED.**
- 👤 **Author:** Mohammed (UsernamUsernam777)
- 📅 **First Published:** 2026 (Check GitHub History for original timestamp evidence).
A calculator in few lines!
```
import customtkinter as ctk
from pypower import GUI
root = ctk.CTk()
entry = ctk.CTkEntry(root, width=250)
entry.pack(pady=10)
GUI.CustomTk.console_num(root, entry_to_insert=entry).pack()
data = GUI.CustomTk.console(root, ['+', '-', '*', '/', 'C', '='], entry_to_insert=entry, return_dic_frame_and_buttons=True)
data['frame'].pack(pady=10)
data['buttons'][4].configure(fg_color="red", command=lambda: entry.delete(0, 'end'))
data['buttons'][5].configure(fg_color="green")
root.mainloop()```

https://github.com/user-attachments/assets/794de796-4692-4a1d-a6d5-f8a9ab3b2c1c
