- **Image Service Menu**  
  A Windows Explorer context menu extension (via `.reg` file) for managing Windows image files using **wimlib-imagex**.  

  **Requirements:**
  - `wimlib-imagex.exe` must be copied into the Windows system directory (`C:\Windows\System32`).  

  **Supported Actions:**
  - `Add` — Add new images to an existing WIM/ESD/SWM.
  - `Append` — Append an image to an existing WIM/ESD/SWM file.
  - `Mount` — Mount a WIM/ESD/SWM image for servicing.
  - `Folder Mounted` — Manage images already mounted to a folder.
  - `Apply` — Apply an image to a drive or folder.
  - `Remove` — Remove images from a WIM/ESD/SWM.
  - `Discard Changes` — Unmount and discard pending modifications.
